# Everywhere App

Use [`expo-router`](https://expo.github.io/router) to build native navigation using files in the `app/` directory, and deploy them **_everywhere_**.

## 🚀 How to use

```bash
$ pnpm install
```

Before you can create a new update, you have to ask Cedric for a project ID. If you have one, put it in your **package.json**'s `everywhere` script.

After doing that, you can create a new update with:

```bash
$ pnpm everywhere --help
```

To open this update, you can either go to the URL or slap that badboy in your dev client:

```bash
$ pnpm android|ios

<open the link by entering: "https://<update>.everywhere.rocks" in the url>
```

You also have access to a few other features, such as:

- See the update information: `https://<update>.everywhere.rocks/--/update`
- See some basic manifest serve stats: `https://<update>.everywhere.rocks/--/stats`

## 📝 Notes

- [Expo Router: Docs](https://expo.github.io/router)
- [Expo Router: Repo](https://github.com/expo/router)
