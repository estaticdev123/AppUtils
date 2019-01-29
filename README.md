# AppUtils

AppUtil Library use for common method that useful on all projects.and some common library include so don't need to add that library in your projects. 

## Getting Started



### Prerequisites

##### Add your project build.gradle

```
allprojects {
                repositories {
                        ...
                        maven { url 'https://jitpack.io' }
                }
        }
```
##### Add your App build.gradle

```
dependencies {
              implementation 'com.github.estaticdev123:AppUtils:v1.0.0'
        }
```


## Deployment

##### Example
##### Display Tost
- Utils.showToast(this,"Message");

##### Check Internet connection
- Utils.hasInternet(this,"Internet connection not available");

##### Load Image
- ImageUtils.displayImage(this,"ImagePath",imageView,R.drawable.background);






