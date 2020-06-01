
import React from 'react'
import { StyleSheet, Text, View } from 'react-native';

export default function Intro() {
    return (
        <View style = {styles.container}>
            <Text>Hello, Welcome to the Future!</Text>
            <View>
                <Text>Showingly</Text>
            </View>
        </View>
    )}

    const styles = StyleSheet.create({
        container: {
            flex: 1,
            backgroundColor: '#fff',
            alignItems: 'center',
            justifyContent: 'center',
            textColor: 'Red',

        },

        bolding: {
            backgroundColor: 'red',
            alignItems: 'center',
        },
    })
