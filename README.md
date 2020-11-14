                                    
   #### Manage res/ layouts
                                     
                                     

**res/layout**

res/layout contains XML screen layout files that can be linked to Activities or other components of your application. The layout files are referenced by its filename, while the each component inside the layout can be referenced by their respective ids.


## Problem

**To much layouts**


<img src="/problem_image.png" width="280" />

## Solution

<img src="/solution_image_1.png" width="280" /> <img src="/solution_image.png" width="280" />


## How to access files?


add to build.gradle:


<img src="/build_gradle_app.jpg" width="280" />

```gradle
    sourceSets {
        main {
            res.srcDirs =
                    [
                            'src/main/res/layouts/login_activity',
                            'src/main/res/layouts/register_activity',
                            'src/main/res/layouts/recower_activity',
                            'src/main/res/layouts',
                            'src/main/res/layouts/history_activity',
                            'src/main/res/layouts/main_activity',
                            'src/main/res/layouts/interfaces',
                            'src/main/res/layouts/reserved_booking_layout',
                            'src/main/res/layouts/navigation_drawer_item_interfaces',
                            'src/main/res'
                    ]
        }
    }
```
<img src="/build_gradle.png" width="280" />


## Layouts in folders 
<img src="/res_directory_in_folders0.png" width="280" />
<img src="/res_directory_in_folders1.png" width="280" />
<img src="/res_directory_in_folders2.png" width="280" />
<img src="/res_directory_in_folders3.png" width="280" />




