# Desktop-Mini-Me
Im going to continue to improve and update the export script but for now i tried to make it as simple and effort free as possible.


How To Install:

to begin you need to download the DesktopMiniMeExporter.UnityPackage from the Releases tab or click here : https://github.com/macery12/Desktop-Mini-Me/releases/latest

After the download is finished the easiest way i have found is to open a already existing unity prodject on your computer containing a vrchat avatar or avatar in general but if needed make a new unity prodject in 2018+ unity and import all of you materialls and fbx files that is needed for your avatar.

Once Completed Import The DesktopMiniMeExporter.UnityPackage downloaded from above.

Once It Has Finished Importing and your avatar is fully set up your going to want your avatar to have some kind of dance or idle animation, currently i do not have a way to change these (Yet) so your going to need to find one or use the one included in the unity package and attach the Dance Controller To the Animator of your avatar as seen below.

![Animator_Attach](https://user-images.githubusercontent.com/57544649/115467699-8bd63f00-a1f7-11eb-8070-6d7b3e9d5546.PNG)

Once that has been completed your going to want to make a prefab of your avatar and attach a it to a AssetBundle as shown below.
![Prefab_Make](https://user-images.githubusercontent.com/57544649/115467985-fd15f200-a1f7-11eb-9a03-0a0a34670af2.PNG)
(Makeing a Prefab of your avatar is as simple as dragging your avatar from the Hierarchy to a folder somewhere in your prodject)

IMPORTANT: Make Sure to Re-Name The Avatar Prefab By Right Clicking The Prefab In Your Files And name it : Avatar, It must be named Avatar (for now) For The DesktopMiniMe application To recognize it!

Now that your avatar is re-named and made into a prefab your going to want to attach it to a assetBundle named: avatar (IMPORTANT: once again it must be named this perfectly and it is case sensitive or else DesktopMiniMeApplication Will not reconise it!)

Once Done Make Sure to coppy These parameters in your prefab to make sure it gets alligned properly inside the DesktopMiniMe Apllication.
![Peramiters Change](https://user-images.githubusercontent.com/57544649/115468903-5df1fa00-a1f9-11eb-94f7-539760f9b0e4.PNG)

Once that is Completed Your almost done, all thats left is by attaching the prefab to a asset bundle and then building the asset bundle. (Be sure to name it "avatar" without quotes) you may need to click on the grey bar at the bottem of the prefab if the asset bundle window is hidden.
![AssetBundle Create](https://user-images.githubusercontent.com/57544649/115469307-01430f00-a1fa-11eb-90d8-71f2ae496e1a.PNG)

Once That is Completed all you need to do is build the asset by clicking as shown in the picture below. (a bug that is known you may need to click the button 1-3 times before the files are created inside your prodject, im aware of this and am working on a way to fix this but this is a work around for now)
![BuildAssetbundle](https://user-images.githubusercontent.com/57544649/115469454-4b2bf500-a1fa-11eb-9d3b-2583c61ce115.PNG)

Once that is done building a new folder should of appeared and should be named "StreamingAssets", inside this folder should be 4 diffrent files.
![StreamingAssets](https://user-images.githubusercontent.com/57544649/115469811-eae98300-a1fa-11eb-89f0-207751007ff7.PNG)

All that is needed now is to copy these 4 files into your desktopMiniMeApplication SteamingAssets Folder,Below is shown where to find this folder.
![Where To find folder](https://user-images.githubusercontent.com/57544649/115470012-4156c180-a1fb-11eb-9ef8-90d2f942592e.PNG)

Once that is Done all you need to do now is to open the DesktopMiniMe application if you have not already and open the menu and click "Import_Avatar", and thats it you now own your own desktopMiniMe!
![import_avatar_button](https://user-images.githubusercontent.com/57544649/115470830-90e9bd00-a1fc-11eb-9546-202fa2be17f8.PNG)

If you have any questions or anything you would like to sugest to me please message me on discord: macery12#7373!





