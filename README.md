# iOS-Developer-Portfolio


Hi, My name is Nasiru Danjuma, an iOS developer from Nigeria. This repository holds a brief insight into the projects I've worked on as well as links to said projects.

# [SnowSeeker](https://github.com/NasiruOjochide/SnowSneeker)

SnowSeeker is an App designed to provide information about ski resorts around the world. It holds information about each resort such as its size, price, elevation and snow. I also provide the facilities available at each resort.
The User can search through a list of resorts to get a particular one, they can sort the list in order of name or country. Upon selecting a resort, they get to see descriptive information about the resort and can also set it as a favourite. I also use SizeClass and dynamicTypeSize to make the app responsive and perfectly scaled on various devices including an iPad. Click on link above to check out code.

<span><img width="300" alt="Screenshot 2023-03-30 at 07 51 52" src="https://user-images.githubusercontent.com/129331000/228753351-53d1705c-7803-4550-ae24-d6686be62965.png">
<img width="300" alt="Screenshot 2023-03-30 at 07 51 07" src="https://user-images.githubusercontent.com/129331000/228753366-b0282726-7f55-4b57-97c1-eee95a42b9d0.png">
<img width="300" alt="Screenshot 2023-03-30 at 07 50 56" src="https://user-images.githubusercontent.com/129331000/228753372-c9213c72-7f5d-477c-b052-89a1db724d12.png"></span>

## Techniques Used
- SwiftUI
  - JSON Decoder and Encoder
  * Reading file from Bundle
  + User Defaults
  - Environment Values


# [Hot Prospects](https://github.com/NasiruOjochide/HotProspectsApp)

This app was designed to act as a sort of reminder to contact people you meet at events but might forget to contact. Users can scan QRCode of other users and they would automatically get the name of the other user. Consequently, at a user's leisure time, they can open the app, see all the folks whose QRCode they scanned, they go ahead to contact them. A user can also mark a friend as contacted or not.
CoreImage was used to generate the QRCode. I downloaded a package into my project that handled the scanning of QRCodes. In the instance where camera isn't available UIKit PHPhotoPicker is used to select an image from photo library. Custom Swipe Actions are also attached to list rows to mark user as contacted or not, as well as send notifications to remind user to contact friend.

<span><img width="300" alt="Screenshot 2023-03-30 at 08 56 04" src="https://user-images.githubusercontent.com/129331000/228769140-49d321e7-c64e-467f-856f-583414600345.png">
<img width="300" alt="Screenshot 2023-03-30 at 08 55 51" src="https://user-images.githubusercontent.com/129331000/228769225-b99734ca-bfed-465e-ac9b-384f67642f32.png">
<img width="300" alt="Screenshot 2023-03-30 at 08 40 00" src="https://user-images.githubusercontent.com/129331000/228769242-a6a3a016-13cc-4b7c-b957-04bb6cd9f76c.png">
<img width="300" alt="Screenshot 2023-03-30 at 08 39 10" src="https://user-images.githubusercontent.com/129331000/228769271-0631e78c-394c-452a-be4e-5f911c83cb13.png">
<img width="300" alt="Screenshot 2023-03-30 at 08 39 02" src="https://user-images.githubusercontent.com/129331000/228769297-3847ba9e-ffd6-4424-aa0d-14668dedcccf.png"></span>

## Techniques Used
- SwiftUI
  - Confirmation dialogs, tab Views, Lists, EnvironmentObjects.
- Local Notifications
- Core Image
- UIImageWriteToSavedPhotosAlbum()
- Save files to document directory



# [Layout and Geomety](https://github.com/NasiruOjochide/Layout-and-Geometry)

This is a practice app for swiftUI features such as alignment guides, absolute positioning using Position() and relative positioning using offset, and using GeometryReader to get the size and frame of views.

https://user-images.githubusercontent.com/129331000/228773318-fddad5ef-3a66-4988-a479-23eda5069082.mov

https://user-images.githubusercontent.com/129331000/228773478-833785b9-2756-464f-aba2-bf3d47c04f43.mov

## Techniques Used

- SwiftUI
  - GeometryReader
  - Custom AlignmentGuide
  - position and offset


# [Image Gallery](https://github.com/NasiruOjochide/ImageGalleryChallenge)

Image Gallery is an app that is able to track a user's location. Whenever a user selects an image from their gallery, the app saves their location at the point that action was carried out. The user's location is then displayed on a map when the image is clicked.

<img width="300" alt="Screenshot 2023-03-30 at 12 38 21" src="https://user-images.githubusercontent.com/129331000/228829495-cc8fc7ef-5d6c-498c-bdf4-849a6a3283f8.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 38 02" src="https://user-images.githubusercontent.com/129331000/228829512-5ebaf5f1-3b99-4fbc-b5a4-ef40149090f9.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 37 53" src="https://user-images.githubusercontent.com/129331000/228829537-04130c26-f0be-41a0-8312-b7cc4b7067b5.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 36 51" src="https://user-images.githubusercontent.com/129331000/228829562-afd4e6b3-3b4e-4204-9f56-c2c223f9a17c.png">


## Techniques Used

- SwiftUI
  - save to documents directory
- PhotosUI
- UIKit
  - PHPickerViewController
- Mapkit
- CoreLocation


# [InstaFilter](https://github.com/NasiruOjochide/InstaFilter)

InstaFilter is an app that allows users to select an image from their photo library, apply filters to it and save edited image back to photo library.
Users can select from a range a filters available. Also The App requires user to authenticate using biometrics before they can access the app.

<img width="300" alt="Screenshot 2023-03-30 at 12 58 16" src="https://user-images.githubusercontent.com/129331000/228829152-542a5658-e3f9-4274-8178-94200f9f8186.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 57 44" src="https://user-images.githubusercontent.com/129331000/228829180-09f5ae83-1b15-4d21-a17e-0887fb2bb6e1.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 58 37" src="https://user-images.githubusercontent.com/129331000/228829213-020bf93a-df6b-4705-8c90-25c4667dfc41.png">
<img width="300" alt="Screenshot 2023-03-30 at 12 58 25" src="https://user-images.githubusercontent.com/129331000/228829240-898ed53a-0e60-4ecc-86a6-a4164db6f82e.png">


## Techniques Used

- SwiftUI
- CoreImage
  - CoreImage.CIFilterBuiltins
- LocalAuthentication
- UIKit
- PhotosUI
