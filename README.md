# realtime-comments-widget-react-sourcecode

Source code for tutorial on building a very simple realtime comments widget with sentiments using - [Next.js](https://learnnextjs.com/), [React](https://reactjs.org/), [Pusher](https://pusher.com/) and [Sentiment Node](https://github.com/thisandagain/sentiment) module. With sentiment analysis, we are able to detect the mood of a person based on the words they use in their messages.

Here is a screenshot of the demo app.

![Chat App Screenshot](https://i.imgur.com/DtLF0GH.png)

**In order to run the demo on your local machine and experiment with the source code, do the following:**

1. **Clone the repository** into a new directory on your machine.

2. **Install the dependencies** by running the following command from the new directory.

```sh
npm install
```

or using `yarn`

```sh
yarn add
```

3. **Create a `.env` file** in the root of the new directory with the following content. Ensure you have already created an application on your [Pusher Dashboard](https://dashboard.pusher.com/) to get your app credentials.

```ini
# Pusher App Credentials

PUSHER_APP_ID=(YOUR_APP_ID)
PUSHER_APP_KEY=(YOUR_APP_KEY)
PUSHER_APP_SECRET=(YOUR_APP_SECRET)
PUSHER_APP_CLUSTER=(YOUR_APP_CLUSTER)
```

4. **Finally, start the demo app** by running the following command. The app will runs on port 3000 except that port is already in use.

```sh
npm run dev
```

For `production`

```sh
npm start
```
