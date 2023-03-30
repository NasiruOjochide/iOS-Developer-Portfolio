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
- Local Notifications
- Core Image
- UIImageWriteToSavedPhotosAlbum()
- Save files to document directory
- Confirmation dialogs, tab Views, Lists, EnvironmentObjects.
