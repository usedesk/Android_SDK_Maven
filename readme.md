[![Юздеск](https://static.tildacdn.com/tild3034-3465-4135-b132-653164653935/logo.png)](https://usedesk.ru/)

Добавьте в `build.gradle` вашего проекта строку:
```
allprojects {
    repositories {
        ...
        maven { url 'https://github.com/usedesk/Android_SDK_Maven/raw/master/' }
    }
}
```

Добавьте в `build.gradle` вашего модуля строку:
```
dependencies {
    ...
    implementation 'ru.usedesk:usedesk_sdk:1.0.2'
    ...
}
```
