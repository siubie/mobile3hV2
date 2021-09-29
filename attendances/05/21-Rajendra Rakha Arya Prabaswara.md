Nama  : Rajendra Rakha Arya P

Kelas : 3H

---

### Summary Minggu Ke-5

**This week the material presented is about animation and multimedia, and also how to use flutter from the ground up.for flutter itself delivered from the installation process to create the widget.**

The material studied is animation and multimedia.

In animation itself there are various kinds, namely, Bitmap Animation, UI Visibility Motion, Physics Based Motion, Animated Layout changes, Animate Between Activity.

- Bitmap Animation = When you want to animate bitmap graphics such as icons or illustrations, you must use the drawable animation API. Typically, these animations are defined statically with drawables, but you can also define animation behavior at runtime.

- UI Visibility Motion = To change the visibility or position of views in your layout, you must include subtle animations to help users understand how the UI changes. To move, reveal, or hide views in the current layout, you can use the property animation system provided by the android.animation package, available on Android 3.0 (API level 11) and higher.

- Physics Based Motion = Physics Based Motion driven by force. Spring force is one of the forces that guide interactivity and motion. The spring force has the following properties: damping and stiffness. In spring-based animation, the value and velocity are calculated based on the spring force applied to each frame. Then your animation should apply real-world physics so it looks natural.

- Animated Layout changes = In Android 4.4 (API level 19) and higher, you can use the transition framework to create animations when you swap layouts in the current activity or fragment. All you need to do is determine the start and end layouts, and what type of animation you want to use. Then the system finds out and runs the animation between the two layouts. You can use this to swap the entire UI or to move/replace just some views.

- Animate Between Activity = On Android 5.0 (API level 21) and higher, you can also create animations that transition between your activities. It's based on the same transition framework described above for animating layout changes, but it lets you animate between layouts in separate activities. You can apply simple animations such as sliding a new activity from the side or fading it, but you can also create animations that transition between shared views in each activity.

Then for multimedia in MediaPlayer overviewnya Android multimedia framework includes support for playing various types of common media, so you can easily integrate audio, video, and images into your applications. You can play audio or video from media files stored in your application resources (raw resources), from standalone files in the file system, or from data streams arriving over a network connection, all using the MediaPlayer API.

**Classes used to play sound and video in Android framework:**

1. Internet Permissions - If you use MediaPlayer to stream network-based content, your application must request network access.

2. Wake Lock Permission - If your player app needs to keep the screen from dimming or the processor from sleeping, or using the MediaPlayer.setScreenOnWhilePlaying() or MediaPlayer.setWakeMode() methods, you must request this permission.ediaPlayer.setScreenOnWhilePlaying() atau MediaPlayer.setWakeMode(), Anda harus meminta izin ini.


