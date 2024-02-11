mport React from 'react';
import { StyleSheet,Text,View} from 'react-native';
export default class App extends React.Component{
render(){
return(
<View style={styles.container}>
<text> Open up App.js to start working on your app!</text>
<text>Chages you make will automatically reload.</text>
<text>Shake your phone to open the developer menu.</text>
</View>
);
}
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    backgroundColor: '#fff',
    alignItems: 'center',
  },
});
