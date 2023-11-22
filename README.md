[![](https://jitpack.io/v/gulnaznaseer21/mylibrary.svg)](https://jitpack.io/#gulnaznaseer21/mylibrary)

# mylibrary

## Getting Started

### Step 1

Add maven repository in project level build.gradle or in latest project setting.gradle file
```
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
```
### Step 2

Add the dependency
```
	dependencies {
	        implementation 'com.github.gulnaznaseer21:mylibrary:1.0'
	}
```
