## Installation

```bash
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
```

## Stack Navigator

```bash
npm install @react-navigation/native-stack
```

```js
<Stack.Navigator>
  <Stack.Screen name='HomeScreen' component={HomeScreen} />
</Stack.Navigator>
```

All screen components receive the navigation prop.

```js
navigation.navigate('name', {
  //my data
})
```

#### Route prop

route props has a params propety.

#### Hooks

useNavigation
useRoute
options
screenOptions
setOptions
