<img src="https://media.tumblr.com/c38c7cb30d3dcdc0d402bd44a53fb4d6/tumblr_inline_mq35gvW8lI1qz4rgp.gif" alt="Coding" width="1000">
<h1 align="center">Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">	, I'm Mahmut Can Fettahoğlu</h1>
<h3 align="center">A software developer who is still a student but improving themselves.</h3>



<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,react,blender,ae,pr,ps,cs,dotnet,bootstrap,wordpress" />
  </a>
</p>



import {View, Text,SafeAreaView,StyleSheet,TouchableOpacity } from 'react-native'
import React from 'react'

const HomePage = () => {
  return (
    <SafeAreaView style={styles.container}>
       <View style={styles.header}></View>
       <View style={styles.body}>
       
       <View style={styles.bodycontainer}>
                    <Text style={styles.bodyyazi}>
                    Hosgeldiniz 
                    
                    </Text>
                </View>
        <View style={styles.bodybutton}> 
          <TouchableOpacity style={styles.subaloncugu}>
            <Text>Tikla</Text>
          </TouchableOpacity>
        </View>
       
       </View>
        <View style={styles.footer}></View>
    </SafeAreaView>
  )
}

const styles =  StyleSheet.create({
    container: {
        flex:1,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#365486',
    },
    header: {
        width:1000,
        height:75,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#4169ab',
        borderBottomWidth: 1, 
        borderBottomColor: 'black', 
    },  
    body: {
        flex:1,
        backgroundColor: '#365486',
        justifyContent: 'center',
        alignItems: 'center'
    },
    footer: {
        width: 1000,
        height:50,
        justifyContent: 'center',
        alignItems: 'center',
        backgroundColor: '#4169ab',
        borderTopWidth: 1, 
        borderTopColor: 'black', 
    },
    bodycontainer:{
      justifyContent: 'start',
      alignItems: 'start'
    },
    bodyyazi:{
      fontWeight: 'bold',
      fontSize:20,
    },
    subaloncugu:{
        alignItems: 'center',
        padding:10,
        backgroundColor: '#0F1035',
        borderWidth: 2,
        borderColor: 'white',
        borderRadius: 10,
        width:125,
        margin:10,
    },
    bodybutton:{
      justifyContent:'center',
      alignItems:'center',
    }
})
export default HomePage
