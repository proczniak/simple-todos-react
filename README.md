# Nothing interesting.
## https://www.meteor.com/tutorials/react/creating-an-app

###commands to issue in order to make this work:

#### To initialize:
```
# meteor create simple-todos-react
# cd simple-todos-react
# meteor add react
```

#### https://www.meteor.com/tutorials/react/collections
```
# meteor mongo
meteor.PRIMARY> db.tasks.insert({ text: "Hello world!", createdAt: new Date() });
```

#### https://www.meteor.com/tutorials/react/running-on-mobile
```
# meteor install-sdk ios
# meteor add-platform ios
# meteor run ios
# meteor install-sdk android
# meteor add-platform android
# meteor run android
```

#### https://www.meteor.com/tutorials/react/adding-user-accounts
```
# meteor add accounts-ui accounts-password
```
##### https://www.meteor.com/tutorials/react/security-with-methods
```
# meteor remove insecure
```

#### Finaly to run
```
# meteor
```
