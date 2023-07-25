# EXPODrod
Aplicação de Browser mobile com acesso a um site, mas navegação boa. criada em EXPO - React Native / WebView

import React from "react";
import { StyleSheet, View, } from "react-native";
import { WebView } from "react-native-webview";

const App = () => {
  return (
    <View style={{ flex: 1 }}>
      <WebView
        source={{ uri: 'https://nomedosite.com.br/' }}
        style={{ flex: 1 }}
        />
    </View>
  );
};

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: "center",
    alignItems: "center",
  },
});


export default App;
