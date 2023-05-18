# React-native-CLI
Navigation in React Native CLI


Android/App/src/main/MainActivity
import android.os.Bundle;

@Override
  protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(null);
  }
  
  
android build.gredle

   ext {
        buildToolsVersion = "33.0.0"
        minSdkVersion = 21
        compileSdkVersion = 33
        targetSdkVersion = 33
        kotlinVersion = "1.8.21"
        // We use NDK 23 which has both M1 support and is the side-by-side NDK version from AGP.
        ndkVersion = "23.1.7779620"
    }
    dependencies {
        classpath("com.android.tools.build:gradle:7.3.1")
        classpath("com.facebook.react:react-native-gradle-plugin")
        classpath ("org.jetbrains.kotlin:kotlin-gradle-plugin:1.8.21")
    }

package.json 

"dependencies": {
    "@react-navigation/native": "^6.0.6",
    "@react-navigation/stack": "^6.3.1",
    "react": "18.2.0",
    "react-native": "0.71.8",
    "react-native-gesture-handler": "^1.10.3",
    "react-native-safe-area-context": "^3.3.2",
    "react-native-screens": "^3.20.0"
  },
