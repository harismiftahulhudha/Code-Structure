# CODE STRUCTURE
* [Explanation of the Kotlin Directory](#penjelasan_direktori_kotlin)
  * [apis Directory](#direktori_apis)
    * [apiservices Directory](#direktori_apiservices)
    * [responses Directory](#direktori_responses)
  * [customcomponents Directory](#direktori_customcomponents)
  * [database Directory](#direktori_database)
    * [Direktori dao](#direktori_dao)
  * [helpers Directory](#direktori_helpers)
  * [mvvm Directory](#direktori_mvvm)
    * [joinmodels Directory](#direktori_joinmodels)
    * [models Directory](#direktori_models)
    * [repositories Directory](#direktori_repositories)
    * [viewmodels Directory](#direktori_viewmodels)
    * [views Directory](#direktori_views)
      * [activities Directory](#direktori_activities)
      * [adapters Directory](#direktori_adapters)
      * [fragments Directory](#direktori_fragments)
      * [viewholders Directory](#direktori_viewholders)
  * [receivers Directory](#direktori_receivers)
  * [services Directory](#direktori_services)
  * [sessions Directory](#direktori_sessions)
  * [utils Directory](#direktori_utils)
* [Explanation of the Resource Directory](#penjelasan_direktori_resource)
  * [anim Directory](#direktori_anim)
  * [drawable Directory](#direktori_drawable)
  * [layout Directory](#direktori_layout)
  * [menu Directory](#direktori_menu)
  * [mipmap-hdpi Directory](#direktori_mipmap_hdpi)
  * [mipmap-mdpi Directory](#direktori_mipmap_mdpi)
  * [mipmap-xhdpi Directory](#direktori_mipmap_xhdpi)
  * [mipmap-xxhdpi Directory](#direktori_mipmap_xxhdpi)
  * [mipmap-xxxhdpi Directory](#direktori_mipmap_xxxhdpi)
  * [values Directory](#direktori_values)
  * [xml Directory](#direktori_xml)
* [Variable Writing Format](#format_penulisan_variabel)
* [Writing Format Fragment Function](#format_penulisan_fungsi_fragment)
* [IMPORTANCE](#penting)
  
# <a name="penjelasan_direktori_kotlin"></a>Explanation of the Kotlin Directory
Following is an explanation of the functions of each directory on the project.

## <a name="direktori_apis"></a>apis Directory
This directory is intended for classes related to http requests.

## <a name="direktori_apiservices"></a>apis Directory > apiservices
This directory is intended for API service class requests. <br/>
for making class **apiservices** required to use `ApiService` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**ApiService**

## <a name="direktori_responses"></a>apis Directory > responses
This directory is intended for classes to hold JSON response data. <br/>
for making class **response** required to use `Response` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Response**

## <a name="direktori_customcomponents"></a>customcomponents Directory
This directory is intended for custom component classes. <br/>
for making class **customcomponents** required to use `CustomComponent` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**CustomComponent**

## <a name="direktori_database"></a>database Directory
This directory is intended for classes related to local databases. <br/>
File naming format **Camel Case**.

## <a name="direktori_dao"></a>database Directory > dao
This directory is intended for classes **DATABASE ACCESS OBJECT** whose function is to query the table <br/>
for making class **dao** required to use `Dao` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Dao**

## <a name="direktori_helpers"></a>helpers Directory
This directory is intended for classes with functions to simplify and summarize programming logic. <br/>
for making class **helpers** required to use `Helper` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Helper**

## <a name="direktori_mvvm"></a>mvvm Directory
This directory is intended for classes related to architecture **Model View ViewModel**.

## <a name="direktori_joinmodels"></a>mvvm Directory > joinmodels
This directory is intended for classes that are intended as object model join queries. <br/>
for making class **models** required to use `Model` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**JoinModel**

## <a name="direktori_models"></a>mvvm Directory > models
This directory is intended for classes intended as object models. <br/>
for making class **models** required to use `Model` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Model**

## <a name="direktori_repositories"></a>mvvm Directory > repositories
This directory is intended for logic classes from architecture **Model View ViewModel**.<br/>
for making class **repositories** required to use `Repository` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Repository**

## <a name="direktori_viewmodels"></a>mvvm Directory > viewmodels
This directory is intended for classes to distribute data from **Repository** to **User Interface**.<br/>
for making class **viewmodels** required to use `ViewModel` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**ViewModel**

## <a name="direktori_views"></a>mvvm Directory > views
This directory is for related classes **User Interface**.

## <a name="direktori_activities"></a>mvvm Directory > views > activities
This directory is intended for classes **Activity**.<br/>
for making class **activities** required to use `Activity` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Activity**

## <a name="direktori_adapters"></a>mvvm Directory > views > adapters
This directory is intended for classes **Adapter**.<br/>
for making class **adapters** required to use `Adapter` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Adapter**

## <a name="direktori_fragments"></a>mvvm Directory > views > fragments
This directory is intended for classes **Fragment**.<br/>
for making class **fragments** required to use `Fragment` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Fragment**

## <a name="direktori_viewholders"></a>mvvm Directory > views > viewholders
This directory is intended for classes **View Holder**.<br/>
for making class **viewholders** required to use `ViewHolder` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**ViewHolder**

## <a name="direktori_receivers"></a>receivers Directory
This directory is intended for classes **Broadcast Receiver**.<br/>
for making class **receivers** required to use `Receiver` at the end of the class name.<br/>
File naming format **Camel Case**.
> ClassName**Receiver**

## <a name="direktori_services"></a>services Directory
This directory is intended for classes **Service**.<br/>
for making class **services** required to use `Service` at the end of the class name.<br/>
> ClassName**Service**

## <a name="direktori_sessions"></a>sessions Directory
This directory is intended for classes **Session**.<br/>
for making class **sessions** required to use `Session` at the end of the class name. <br/>
File naming format **Camel Case**.
> NamaClass**Session**

## <a name="direktori_utils"></a>utils Directory
This directory is intended for utility-related classes **Generic Class and Configuration**.<br/>
File naming format **Camel Case**.

# <a name="penjelasan_direktori_resource"></a>Explanation of the Resource Directory
Following is an explanation of the functions of each directory on the project.

## <a name="direktori_anim"></a>anim Directory
This directory is intended for xml files with animation functions.
for making xml it is required to use `anim` at the beginning of the xml name. <br/>
File naming format **Snake Case**.
> **anim**_file_name

## <a name="direktori_drawable"></a>drawable Directory
This directory is intended for xml files with the selector function.
for making xml required to use `bg` at the beginning of the xml name.<br/>
File naming format **Snake Case**.
> **bg**_file_name

## <a name="direktori_layout"></a>layout Directory
This directory is intended for xml files with a user interface layout function.
for making xml required to use `activity / fragment / popup / item / content / header` at the beginning of the xml name. And **_reference_the_layout_function**. <br/>
File naming format **Snake Case**.
> **activity**_chat<br/>
**fragment**_chat<br/>
**popup**_delete_verification<br/>
**item**_chat<br/>
**content**_body_chat<br/>
**header**_chat

## <a name="direktori_menu"></a>menu Directory
This directory is intended for xml files with menu functions.
for making xml required to use `menu` at the end of the xml name.<br/>
File naming format **Snake Case**.
> chat_**menu**

## <a name="direktori_mipmap_hdpi"></a>mipmap-hdpi Directory
This directory is intended for hdpi size icon files.

## <a name="direktori_mipmap_mdpi"></a>mipmap-mdpi Directory
This directory is intended for mdpi size icon files.

## <a name="direktori_mipmap_xhdpi"></a>mipmap-xhdpi Directory
This directory is intended for xhdpi size icon files.

## <a name="direktori_mipmap_xxhdpi"></a>mipmap-xxhdpi Directory
This directory is intended for xxhdpi size icon files.

## <a name="direktori_mipmap_xxxhdpi"></a>mipmap-xxxhdpi Directory
This directory is intended for xxxhdpi size icon files.

## <a name="direktori_values"></a>values Directory
This directory is intended for global variable xml files. <br/>
for naming variables required to use `color` at the beginning of the xml name and must use the format **Camel Case**.
> colorWhite<br/>colorBlue

## <a name="direktori_xml"></a>xml Directory
This directory is intended for xml files with configuration functions. <br/>
File naming format **Snake Case**.
> provider_paths

# <a name="format_penulisan_variabel"></a>Variable Writing Format
Writing Format **VARIABELS** or **ID** `MUST USE THE FORMAT CAMEL CASE`.<br/>
Specific Writing **CONSTANT VARIABLES** `MUST USE THE FORMAT FORMAT ALL CAPS`.<br/>
Specifically for Making Global Variables that are Protected please add them to `build.gradle`
```
    defaultConfig {
        addConstant("VARIABLES_NAME", "VALUES")
    }
```
For Call Variables in the Kotlin Class
```
    BuildConfig.VARIABLES_NAME
```
For Call Variables in Manifest
```
    <meta-data android:name="packagename" android:value="${VARIABLES_NAME}"/>
```

# <a name="format_penulisan_fungsi_fragment"></a>Writing Format Fragment Function
```
 variable TAG // optional
 |
 |
 companion object {} // optional for static variables
 |
 |
 onCreateView()
 |
 |
 Components related to the Activity of Fragments
 example: Textview of Activity, Activity, Button of Activity, etc.
 |
 |
 Variables related to Activity of Fragment
 |
 |
 onActivityCreated() // initialize the component of activity in this function.
 |
 |
 onHiddenChanged() // optional
 |
 |
 ViewModel from Fragment
 |
 |
 Component from Fragment
 |
 |
 Variables from Fragment
 |
 |
 onCreateView() // component initialization, variables in this function
 |
 |
 onStart() // the onStart function usually is used to register the broadcast receiver
 |
 |
 onStop() // the onStart function usually is used to unregister the broadcast receiver
 |
 |
 initComponents() // optional. this function only contains the initialization of the view model, component and fragment variables. If this function is created. Call this function inside the onCreateView () function
 |
 |
 subscribeListeners() // This function contains the listener function on the component of the fragment. Call this function after the initComponents () function inside the onCreateView () function
 |
 |
 subscribeBroadcastReceivers() // this function contains listening broadcastReceiver. Call this function after the subscribeListeners () function in the onCreateView () function
 |
 |
 subscribeObservers() // this function contains an observer from the view model. Call this function after the subscribeBroadcastReceivers () function in the onCreateView () function
 |
 |
 Custom function of fragment
 |
 |
 The override function of the lifecycle fragment
```

# <a name="penting"></a>IMPORTANCE
**MAKE IT A HABIT TO REFORMAT THE CODE** `CTRL + ALT + L`
