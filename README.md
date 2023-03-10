
# Flutter MapπΊοΈ and Auth.

An application through which you can log in in more than one way, and you can see the map and the road you want to reach.

![Flutter Map and Auth](https://user-images.githubusercontent.com/60518534/213876228-0b5bed0b-dbe5-4efc-a5f2-911def1c4084.gif)


## β Tools Used
- Flutter 
- Dart
- Animation
- Firebase

## β¨ Features
β Beautiful UI.\
β Amazing animation.\
β Sign in with Facebook.\
β Sign in with Google.\
β Sign in with GitHub.\
β Sign in with Phone Number.\


## Directory Structure

```
lib
β
βββββ core
β     ββββ assets
β     β    βββ images
β     β         βββ app_images.dart
β     ββββ constant
β     β     βββ failure_messages.dart
β     β     βββ strings.dart
β     ββββ enum
β     β     βββ auth_enum.dart
β     ββββ error
β     β     βββ exceptions.dart
β     β     βββ failures.dart
β     ββββ network
β     β     βββ apis.dart
β     β     βββ dio_helper.dart
β     β     βββ end_points.dart
β     ββββ routes
β     β     βββ router.dart
β     β     βββ routes.dart
β     ββββ theme
β     β     βββ colors.dart
β     β     βββ values_manager.dart
β     β     βββ themes.dart
β     ββββ utils
β     β     βββ app_utils.dart
β     β     βββ location_helper.dart
β     ββββ widgets
β           βββ animated_button_widget.dart
βββββ features
β     ββββ auth
β     β     βββ data
β     β     β   ββββ datasources
β     β     β   β   βββ auth_remote_datasources.dart
β     β     β   ββββ repositories
β     β     β       βββ auth_repo_impl.dart
β     β     βββ domain
β     β     β   ββββ repositories
β     β     β   β   βββ auth_repo.dart
β     β     β   ββββ usecases
β     β     β       βββ sign_in_with_facebook_usecase.dart
β     β     β       βββ sign_in_with_gitHub_usecase.dart
β     β     β       βββ sign_in_with_google_usecase.dart
β     β     β       βββ sign_in_with_phone_number_usecase.dart
β     β     βββ presentation
β     β         ββββ bloc
β     β         β   βββ cubit
β     β         β       βββ login_cubit.dart
β     β         β       βββ login_state.dart
β     β         β       βββ auth_cubit.dart
β     β         β       βββ auth_state.dart
β     β         ββββ pages
β     β         β   βββ auth_page.dart
β     β         β   βββ otp_page.dart
β     β         β   βββ login_page.dart
β     β         ββββ widgets
β     β             βββ intro_text.dart
β     β             βββ logo_widget.dart
β     β             βββ next_button.dart
β     β             βββ or_widget.dart
β     β             βββ phone_form_field.dart
β     ββββ map
β           βββ data
β           β   ββββ datasources
β           β   β   βββ map_remote_datasources.dart
β           β   ββββ models
β           β   β   βββ place_autocomplete_model.dart
β           β   β   βββ place_details_model.dart
β           β   β   βββ place_directon_model.dart
β           β   β   βββ place_suggestion_model.dart
β           β   ββββ repositories
β           β       βββ map_repo_impl.dart
β           βββ domain
β           β   ββββ repositories
β           β   β   βββ map_repo.dart
β           β   ββββ usecases
β           β       βββ place_details_usecase.dart
β           β       βββ place_directions_usecase.dart
β           β       βββ places_suggestions_usecases.dart
β           βββ presentation
β               ββββ bloc
β               β   βββ cubit
β               β       βββ map_cubit.dart
β               β       βββ map_state.dart
β               ββββ pages
β               β   βββ map_page.dart
β               ββββ widgets
β                   βββ build_map.dart
β                   βββ build_places_list.dart
β                   βββ distance_and_time_widget.dart
β                   βββ floating_search_bar.dart
β                   βββ place_item_widget.dart
βββββ bloc_observer.dart
βββββ injection_container.dart
βββββ main.dart    
```
## Video
https://user-images.githubusercontent.com/60518534/213737814-cd23db24-0523-4066-b5cf-b4cc0b4e1477.mp4

## Packages

![image](https://user-images.githubusercontent.com/60518534/213874166-553b590d-42c4-4400-b220-2bef42794810.png)

## Feedback

If you have any feedback, please reach out to us at mahmoud3laa2210@gmail.com

## π You can follow me on

[![portfolio](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudAlaa22)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoudalaa2210/)
