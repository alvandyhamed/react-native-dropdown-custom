# react-native-dropdown-custom

component for react-native (Android &amp;&amp; IOS) Custom style and custom font style . Easy to use.

yarn add https://github.com/alvandyhamed/react-native-dropdown-custom
Or
npm i https://github.com/alvandyhamed/react-native-dropdown-custom

## Demo
<kbd>
  <img src="https://github.com/alvandyhamed/react-native-dropdown-custom/blob/master/test.gif?raw=true">
</kbd>


## How to use 
Run : 
    
    `$ npm i https://github.com/alvandyhamed/react-native-dropdown-custom`
    or
    `$ yarn add npm i https://github.com/alvandyhamed/react-native-dropdown-custom`

Add the following code in your component :
              
        <View style={{flex: 1}}>

                <DropdownMenu
                    style={{flex: 1}}
                    bgColor={'#ffffff'}
                    tintColor={'#120005'}
                    activityTintColor={Color.primarycolor}
                    // arrowImg={}
                    // checkImage={}
                    optionTextStyle={{color: '#333333',fontFamily:Font.main}}
                    titleStyle={{color: '#333333',fontFamily:Font.main,borderBottomWidth:0.5,
                        borderColor:'#adadad',flex:1}}
                    titreStyle={{color: '#adadad',fontFamily:Font.main,paddingLeft:10,paddingRight:10}}
                    titr={'عبدالله'}
                    maxHeight={300}
                    handler={(selection, row) => this.setState({text: data[selection][row]})}
                    data={data}
                    styleborder={{borderWidth:0.5,borderRadius:4}}
                >


                </DropdownMenu>
            </View>
### this version has customable style for android https://github.com/WheelerLee/react-native-dropdown-menu
