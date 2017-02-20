# react-native-expandable-view

[![NPM Version](https://img.shields.io/npm/v/react-native-expandable-view.svg?style=flat)](https://www.npmjs.com/package/react-native-expandable-view)
[![NPM Downloads](https://img.shields.io/npm/dm/react-native-expandable-view.svg?style=flat)](https://www.npmjs.com/package/react-native-expandable-view)

---
An expandable view for react native, working both on Android and iOS.

## <a name='install'>Installation</a>
```
npm install react-native-expandable-view --save
```

## <a name='usage'>Usage</a>
```
import ExpandableView from 'react-native-expandable-view';
```

Then wrap the view you wish to be expandable. 

It will automatically become expandable if the height of its content exceeds the given initial manxium height.

```js
<ExpandableView>
    <View>
        <Text>My expandable view</Text>
    </View>
</ExpandableView>
```

## Properties

| Prop | Description | Default |
|---|---|---|
|**`intialMaxHeight`**|The maxmium height your content can be before it becomes expandable|500|
|**`text`**|Text for the expand button|'Tap here to expand'|

