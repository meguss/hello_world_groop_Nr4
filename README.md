import React from 'react';
import { StyleSheet, Text, Image, View } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text>Hello World.</Text>
      <Text>From grop Nr. 4 </Text>
      <Text>From Renāte Smirnova.  </Text>
      <Text>From Oļegs Gluhanuks. </Text>
      <Text>From Inguss Ikstens. </Text>
       <Image
        style={styles.stretch}
        source={require('@expo/snack-static/react-native-logo.png')}
      />
      <Image
        style={styles.tinyLogo}
        source={{
          uri: 'https://images.app.goo.gl/w9FWqJTYSj6R9ZgS8',
        }}
      />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});
