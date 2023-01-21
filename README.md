
# Flutter Map🗺️ and Auth.

An application through which you can log in in more than one way, and you can see the map and the road you want to reach.

![Flutter Map and Auth](https://user-images.githubusercontent.com/60518534/213876228-0b5bed0b-dbe5-4efc-a5f2-911def1c4084.gif)


## ⚙ Tools Used
- Flutter 
- Dart
- Animation
- Firebase

## ✨ Features
✔ Beautiful UI.\
✔ Amazing animation.\
✔ Sign in with Facebook.\
✔ Sign in with Google.\
✔ Sign in with GitHub.\
✔ Sign in with Phone Number.\


## Directory Structure

```
lib
│
│──── core
│     │─── assets
│     │    └── images
│     │         └── app_images.dart
│     │─── constant
│     │     │── failure_messages.dart
│     │     └── strings.dart
│     │─── enum
│     │     └── auth_enum.dart
│     │─── error
│     │     │── exceptions.dart
│     │     └── failures.dart
│     │─── network
│     │     │── apis.dart
│     │     │── dio_helper.dart
│     │     └── end_points.dart
│     │─── routes
│     │     │── router.dart
│     │     └── routes.dart
│     │─── theme
│     │     │── colors.dart
│     │     │── values_manager.dart
│     │     └── themes.dart
│     │─── utils
│     │     │── app_utils.dart
│     │     └── location_helper.dart
│     └─── widgets
│           └── animated_button_widget.dart
│──── features
│     │─── auth
│     │     │── data
│     │     │   │─── datasources
│     │     │   │   └── auth_remote_datasources.dart
│     │     │   └─── repositories
│     │     │       └── auth_repo_impl.dart
│     │     │── domain
│     │     │   │─── repositories
│     │     │   │   └── auth_repo.dart
│     │     │   └─── usecases
│     │     │       │── sign_in_with_facebook_usecase.dart
│     │     │       │── sign_in_with_gitHub_usecase.dart
│     │     │       │── sign_in_with_google_usecase.dart
│     │     │       └── sign_in_with_phone_number_usecase.dart
│     │     └── presentation
│     │         │─── bloc
│     │         │   └── cubit
│     │         │       │── login_cubit.dart
│     │         │       │── login_state.dart
│     │         │       │── auth_cubit.dart
│     │         │       └── auth_state.dart
│     │         │─── pages
│     │         │   │── auth_page.dart
│     │         │   │── otp_page.dart
│     │         │   └── login_page.dart
│     │         └─── widgets
│     │             │── intro_text.dart
│     │             │── logo_widget.dart
│     │             │── next_button.dart
│     │             │── or_widget.dart
│     │             └── phone_form_field.dart
│     └─── map
│           │── data
│           │   │─── datasources
│           │   │   └── map_remote_datasources.dart
│           │   │─── models
│           │   │   │── place_autocomplete_model.dart
│           │   │   │── place_details_model.dart
│           │   │   │── place_directon_model.dart
│           │   │   └── place_suggestion_model.dart
│           │   └─── repositories
│           │       └── map_repo_impl.dart
│           │── domain
│           │   │─── repositories
│           │   │   └── map_repo.dart
│           │   └─── usecases
│           │       │── place_details_usecase.dart
│           │       │── place_directions_usecase.dart
│           │       └── places_suggestions_usecases.dart
│           └── presentation
│               │─── bloc
│               │   └── cubit
│               │       │── map_cubit.dart
│               │       └── map_state.dart
│               │─── pages
│               │   └── map_page.dart
│               └─── widgets
│                   │── build_map.dart
│                   │── build_places_list.dart
│                   │── distance_and_time_widget.dart
│                   │── floating_search_bar.dart
│                   └── place_item_widget.dart
│──── bloc_observer.dart
│──── injection_container.dart
└──── main.dart    
```
## Video
https://user-images.githubusercontent.com/60518534/213737814-cd23db24-0523-4066-b5cf-b4cc0b4e1477.mp4

## Packages

![image](https://user-images.githubusercontent.com/60518534/213874166-553b590d-42c4-4400-b220-2bef42794810.png)

## Feedback

If you have any feedback, please reach out to us at mahmoud3laa2210@gmail.com

## 🔗 You can follow me on

[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudAlaa22)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudalaa2210/)
