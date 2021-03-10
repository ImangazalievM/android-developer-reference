# Android UI
- [**App styling:**](#app-styling)
  - [Window, Insets](#window-insets)
- [**Resources**](#resources)
- **[Views](#views)**:
  - [Custom views](#custom-views)
  - [View Outline](#view-outline)
  - [Android Canvas](#android-canvas)
  - [Clipping, PorterDuff](#clipping-porterduff)
- [**Animations**](#animations):
  - [Android Transitions](android-transitions)
  - [ValueAnimator, ObjectAnimator](valueanimator-objectanimator)
- [**Gestures**](#gestures)
- **[Material Components & Layouts](#material-components--layouts):**
  - [CoordinatorLayout, AppBarLayout](#coordinatorlayout-appbarlayout)
  - [ConstraintLayout, MotionLayout](#constraintlayout-motionlayout)
- **[RecyclerView](#recyclerview):**
  - [Adapter](#adapter)
  - [ItemDecoration](#itemdecoration)
  - [SnapHelper](#snaphelper)
  - [LayoutManager](#layoutmanager)
  - [ItemAnimator](#itemanimator)
  - [DiffUtil](#diffutil)
  - [State Restoration Policy](#state-restoration-policy)
  - [Animations](#animations-1)
  
 ___
  
## App styling

- [Android Styling: themes overlay](https://medium.com/androiddevelopers/android-styling-themes-overlay-1ffd57745207)
- [Android Styling: prefer theme attributes](https://medium.com/androiddevelopers/android-styling-prefer-theme-attributes-412caa748774)
- [Android styling: common theme attributes](https://medium.com/androiddevelopers/android-styling-common-theme-attributes-8f7c50c9eaba)
- [Android styling: themes vs styles](https://medium.com/androiddevelopers/android-styling-themes-vs-styles-ebe05f917578)
- [Android Themes & styles, a real architecture](https://blog.octo.com/en/android-themes-styles-a-real-architecture/)
- [What’s your text’s appearance?](https://medium.com/androiddevelopers/whats-your-text-s-appearance-f3a1729192d)
- [DayNight — Adding a dark theme to your app](https://medium.com/androiddevelopers/appcompat-v23-2-daynight-d10f90c83e94)
- [Dark Mode Musings: Beware of the Context](https://medium.com/over-engineering/dark-mode-musings-beware-of-the-context-59baefc3864d)

## Material Components

- [Migrating to Material Components](https://medium.com/androiddevelopers/migrating-to-material-components-for-android-ec6757795351)
- [Material Theming with MDC: Shape](https://medium.com/androiddevelopers/material-theming-with-mdc-shape-126c4e5cd7b4)
- [Material Theming with MDC: Color](https://medium.com/androiddevelopers/material-theming-with-mdc-color-860dbba8ce2f)
- [Material Theming with MDC: Type](https://medium.com/androiddevelopers/material-theming-with-mdc-type-8c2013430247)
- [Dark Theme with MDC](https://medium.com/androiddevelopers/dark-theme-with-mdc-4c6fc357d956)
- 📺 [Developing themes with style (Android Dev Summit '19)](https://youtu.be/Owkf8DhAOSo)

## Resources

- [Auto fetching string resource](https://proandroiddev.com/auto-fetching-string-resources-31788ceecf04)

### Layouts
- [Some common mistakes when doing layout in Android](https://medium.com/swlh/some-common-mistakes-in-doing-layout-in-android-a8ee035f199c)
= [Writing Performant Layouts](https://proandroiddev.com/writing-performant-layouts-3bf2a18d4a61)
- [AsyncLayoutInflater](https://blog.stylingandroid.com/asynclayoutinflater/)
- [LayoutInflater: Friend or Foe?](https://academy.realm.io/posts/layoutinflater-droid-kaigi-2017-jenx/)

### Vector images

- [Using vector assets in Android apps](https://medium.com/androiddevelopers/using-vector-assets-in-android-apps-4318fd662eb9)
- [Draw a Path: Rendering Android VectorDrawables](https://medium.com/androiddevelopers/draw-a-path-rendering-android-vectordrawables-89a33b5e5ebf)
- [Understanding Android’s vector image format: VectorDrawable](https://medium.com/androiddevelopers/understanding-androids-vector-image-format-vectordrawable-ab09e41d5c68)
- [Material Motion with MDC](https://medium.com/androiddevelopers/material-motion-with-mdc-c1f09bb90bf9)

### Fonts

- [Variable Fonts in Android O](https://medium.com/over-engineering/variable-fonts-in-android-p-c5c918275646)

## Window, Insets
- [WindowInsets — listeners to layouts](https://medium.com/androiddevelopers/windowinsets-listeners-to-layouts-8f9ccc8fa4d1)
- [Animating your keyboard (part 1)](https://medium.com/androiddevelopers/animating-your-keyboard-fb776a8fb66d)
- [Animating your keyboard (part 2): reacting to WindowInset animations](https://medium.com/androiddevelopers/animating-your-keyboard-reacting-to-inset-animations-839be3d4c31b)
- [Window Insets and Keyboard Animations Tutorial for Android 11](https://www.raywenderlich.com/18393648-window-insets-and-keyboard-animations-tutorial-for-android-11)
- [Insetter](https://chrisbanes.github.io/insetter)
- [curtains](https://github.com/square/curtains) - The missing Android Window APIs!

## Views

- [Why would I want to fitsSystemWindows?](https://medium.com/androiddevelopers/why-would-i-want-to-fitssystemwindows-4e26d9ce1eec#.tjiswxqwo)
- [The little secret of android:animateLayoutChanges](https://proandroiddev.com/the-little-secret-of-android-animatelayoutchanges-e4caab2fddec)
- [Drag and drop in Android. All you need to know](https://proandroiddev.com/drag-and-drop-in-android-all-you-need-to-know-6df8babfb507)

### Custom views
- [Ultimate Guide To Android Custom View](https://vladsonkin.com/ultimate-guide-to-android-custom-view/)
- [Android: draw a custom view](https://proandroiddev.com/android-draw-a-custom-view-ef79fe2ff54b)
- [Android: bring life to your custom view](https://proandroiddev.com/android-bring-life-to-your-custom-view-8604ab3967b3)
- [How to test a custom Android view with Robolectric](https://plusmobileapps.com/2020/12/14/android-custom-view-testing.html)
- [Custom view from scratch. Part I](https://medium.com/revolut/custom-view-from-scratch-part-i-931178481903)
- [Custom view from scratch. Part II. Canvas](https://medium.com/revolut/custom-view-from-scratch-part-ii-canvas-74982b1d2d7c)
- [Custom view from scratch. Part III. Performance and optimisation](https://medium.com/revolut/custom-view-from-scratch-part-iii-performance-and-optimisation-54cb6ac57e4b)
- [Custom Android Views: Graph View and Drawing on the Canvas](https://medium.com/@supahsoftware/custom-android-views-graph-view-and-drawing-on-the-canvas-d03c2ea2b703)
- [Custom Android Views: Search View and Circular Reveal Animations](https://medium.com/@supahsoftware/custom-android-views-search-view-and-circular-reveal-animations-7bf2dadc800)
- [Custom Android Views: Carousel RecyclerView](https://medium.com/@supahsoftware/custom-android-views-carousel-recyclerview-7b9318d23e9a)
- [Messengers-like ImageView](https://proandroiddev.com/messengers-like-imageview-90e9f1da19f4)
- [Android Custom View Level 1 Basic Terms and Creation of Custom View](https://proandroiddev.com/android-custom-view-level-1-67ed1c3febe1)
- [Android Custom Views Level 2 AttributeSet](https://proandroiddev.com/android-custom-views-level-2-7a0f110a2ce9)
- [Android Custom View Level 3 View Life-Cycle](https://proandroiddev.com/android-custom-view-level-3-81e767c8cc75)

### Android Canvas
- [Getting Started with Android Canvas Drawing](https://medium.com/over-engineering/getting-started-with-drawing-on-the-android-canvas-621cf512f4c7)
- [Learn All Android Canvas Draw Functions](https://medium.com/mobile-app-development-publication/learn-all-android-canvas-draw-functions-dd5d6595884a)
- [Android Canvas APIs with Kotlin and KTX](https://medium.com/over-engineering/android-canvas-apis-with-kotlin-and-ktx-d92d4622ce09)
- [Playing with Paths](https://medium.com/androiddevelopers/playing-with-paths-3fbc679a6f77)
- [Playing with Android canvas drawVertices](https://medium.com/mobile-app-development-publication/playing-with-android-canvas-drawvertices-32266c480ab6)
- [Learn to create a Paint Application for Android](https://ssaurel.medium.com/learn-to-create-a-paint-application-for-android-5b16968063f8)
- [A guide to drawing in android](https://android.jlelse.eu/a-guide-to-drawing-in-android-631237ab6e28)
- [Exploring Android Canvas Drawing— For Shapes, Bitmaps andCustom views](https://android.jlelse.eu/android-canvas-for-drawing-and-custom-views-e1a3e90d468b)
- [Android Canvas Drawing: Useful Graphics Classes & Operations](https://medium.com/over-engineering/android-canvas-drawing-useful-graphics-classes-operations-2803e435e848)
- [Expounding Android Canvas’ DrawText](https://medium.com/mobile-app-development-publication/expounding-android-canvas-drawtext-bae3d4fabc5a)
- [Canvas : The Real Play Ground! Android](https://android.jlelse.eu/canvas-the-real-play-ground-android-c0faa4b79943)
- [Drawing multiline text to Canvas on Android](https://medium.com/over-engineering/drawing-multiline-text-to-canvas-on-android-9b98f0bfa16a)

### Clipping, PorterDuff

- [Android UI: Creating a layout rounded only in the top](https://medium.com/@iamsadesh/android-ui-creating-a-layout-rounded-only-in-the-top-d60514ccab77)
- [Clipping and shadows on Android](https://medium.com/@Zielony/clipping-and-shadows-on-android-e702a0d96bd4)
- [PorterDuff.Mode](https://developer.android.com/reference/android/graphics/PorterDuff.Mode)
- [Manipulating images and Drawables with Android’s ColorFilter](https://medium.com/over-engineering/manipulating-images-and-drawables-with-androids-colorfilter-25bf061843e7)
- [The power of Android Porter/Duff Mode with View Animation](https://android.jlelse.eu/the-power-of-android-porter-duff-mode-28b99ade45ec)

### TextView

- [Spantastic text styling with Spans](https://medium.com/androiddevelopers/spantastic-text-styling-with-spans-17b0c16b4568)
- [What’s your text’s appearance?](https://medium.com/androiddevelopers/whats-your-text-s-appearance-f3a1729192d)
- [Underspanding spans](https://medium.com/androiddevelopers/underspanding-spans-1b91008b97e4)
- [Working with spans in Android](https://programmerr47.medium.com/working-with-spans-in-android-ca4ab1327bc4)
- [Creating custom Text Selection actions with ACTION_PROCESS_TEXT](https://medium.com/androiddevelopers/custom-text-selection-actions-with-action-process-text-191f792d2999#.v9tqu854k)
- [Async Text Loading in Android with PrecomputedText](https://proandroiddev.com/async-text-loading-in-android-with-precomputedtext-93aa131b0e5b)
- [Using gradient for styling text](https://medium.com/plum-engineering/using-gradient-for-styling-text-1df9c87c0869)

### ViewPager

- [ViewPager2 under the Hood](https://helw.net/2019/02/08/viewpager2-under-the-hood/?__s=xjbznawfpuk7bngq7fa6)

## Animations

- [Animating on a Schedule](https://medium.com/androiddevelopers/animating-on-a-schedule-8a90d812ae4)
- [Suspending over views](https://medium.com/androiddevelopers/suspending-over-views-19de9ebd7020)
- [Suspending over views — example](https://medium.com/androiddevelopers/suspending-over-views-example-260ce3dc9100)
- [Android: Using Physics-based Animations in Custom Views](https://medium.com/over-engineering/android-using-physics-based-animations-in-custom-views-springanimation-5c3a70c0dd0d)
- [Complex UI/Animations on Android](https://proandroiddev.com/complex-ui-animation-on-android-8f7a46f4aec4)
- [Workcation App – Part 2. Animating Markers with MapOverlayLayout](https://www.thedroidsonroids.com/blog/workcation-app-part-2-animating-markers-with-mapoverlaylayout)
- [Workcation App – Part 3. RecyclerView interaction with Animated Markers](https://www.thedroidsonroids.com/blog/workcation-app-part-3-recyclerview-interaction-with-animated-markers/)
- [How We Developed Jelly ToolBar Animation for Android in Kotlin](https://yalantis.com/blog/toolbar-jelly-animation-kotlin-android/)
- [Introduction to Physics-based animations in Android](https://proandroiddev.com/introduction-to-physics-based-animations-in-android-1be27e468835)
- [Bringing smooth animation transitions to Android](https://medium.com/wirecube-software-engineering/bringing-smooth-animation-transitions-to-android-88786347e512)
- [Randomized, endless animation using TimeAnimator](https://medium.com/@patrick.elmquist/continuous-animation-using-timeanimator-5b8a903603fb)

### Transitions
- [Fragment transitions with shared elements](https://medium.com/@bherbst/fragment-transitions-with-shared-elements-7c7d71d31cbb)
- [Hidden mistakes with Shared Element Transitions](https://medium.com/redmadrobot-mobile/hidden-mistakes-with-shared-element-transitions-65d79831c63)
- [Workcation App – Part 1. Fragment custom transition](https://www.thedroidsonroids.com/blog/workcation-app-part-1-fragments-custom-transition)
- [Workcation App – Part 4. Shared Element Transition with RecyclerView and Scenes](https://www.thedroidsonroids.com/blog/workcation-app-part-4-shared-element-transition-recyclerview-scenes)

## Gestures

- [Gesture Navigation: going edge-to-edge (I)](https://medium.com/androiddevelopers/gesture-navigation-going-edge-to-edge-812f62e4e83e)
- [Gesture Navigation: handling visual overlaps (II)](https://medium.com/androiddevelopers/gesture-navigation-handling-visual-overlaps-4aed565c134c)
- [Gesture Navigation: handling gesture conflicts (III)](https://medium.com/androiddevelopers/gesture-navigation-handling-gesture-conflicts-8ee9c2665c69)
- [Gesture Navigation: immersive modes (IV)](https://medium.com/androiddevelopers/gesture-navigation-immersive-modes-43f2d37a925d)

## Material Components & Layouts

### CoordinatorLayout, AppBarLayout

- [Intercepting everything with CoordinatorLayout Behaviors](https://medium.com/androiddevelopers/intercepting-everything-with-coordinatorlayout-behaviors-8c6adc140c26)

### ConstraintLayout, MotionLayout

- [ConstraintLayout.com](https://constraintlayout.com/)
- [Guide to ConstraintLayout](https://medium.com/@loutry/guide-to-constraintlayout-407cd87bc013)
- [Exploring the new Android ConstraintLayout](https://medium.com/exploring-android/exploring-the-new-android-constraintlayout-eed37fe8d8f1)
- [Introducing Constraint Layout 2.0](https://medium.com/androiddevelopers/introducing-constraint-layout-2-0-9daa3e99995b)
- [ConstraintLayout Chains](https://medium.com/@nomanr/constraintlayout-chains-4f3b58ea15bb)
- [Introducing Constraint Layout 1.1](https://medium.com/androiddevelopers/introducing-constraint-layout-1-1-d07fc02406bc)
- [Constraint Layout 2.0 — Flow Tag Introduction](https://medium.com/@nickand/constraint-layout-2-0-flow-layout-introduction-539350ef994d)
- [A Battle towards Performance- Constraint Layout vs Other Layouts(Part -1)](https://proandroiddev.com/constraintlayout-vs-other-layouts-a-battle-towards-performance-part-1-14d8116e876e)
- [ConstraintLayout Flow, Bye Bye to LinerLayout??](https://medium.com/@tapanrgohil/constraintlayout-flow-bye-bye-to-linerlayout-78fd7fa9b679)
- [ConstraintLayout Flow: Simple Grid Building Without Nested Layouts](https://www.bignerdranch.com/blog/constraintlayout-flow-simple-grid-building-without-nested-layouts/)
- [Awesomeness of ConstraintLayout Flow](https://proandroiddev.com/awesomeness-of-constraintlayout-flow-aa0b5edd5df)
- [Beautiful animations using Android ConstraintLayout](https://robinhood.engineering/beautiful-animations-using-android-constraintlayout-eee5b72ecae3)

**MotionLayout**
- [Introducing the Motion Editor](https://android-developers.googleblog.com/2020/07/introducing-motion-editor.html)
- [Introduction to MotionLayout (part I)](https://medium.com/google-developers/introduction-to-motionlayout-part-i-29208674b10d)
- [Introduction to MotionLayout (part II)](https://medium.com/google-developers/introduction-to-motionlayout-part-ii-a31acc084f59)
- [Introduction to MotionLayout (part III)](https://medium.com/google-developers/introduction-to-motionlayout-part-iii-47cd64d51a5)
- [Defining motion paths in MotionLayout](https://medium.com/google-developers/defining-motion-paths-in-motionlayout-6095b874d37)
- [Complex UI/Animations on Android — featuring MotionLayout](https://proandroiddev.com/complex-ui-animations-on-android-featuring-motionlayout-aa82d83b8660)
- [Circular carousel with MotionLayout](https://medium.com/@rodrigomartind/circular-carousel-with-motionlayout-658d9c44c925)

## RecyclerView

- [Anatomy of RecyclerView. Part 1](https://android.jlelse.eu/anatomy-of-recyclerview-part-1-a-search-for-a-viewholder-404ba3453714)
- [Anatomy of RecyclerView. Part 2](https://android.jlelse.eu/anatomy-of-recyclerview-part-1-a-search-for-a-viewholder-continued-d81c631a2b91)
- [How RecyclerView works internally?](https://medium.com/1mgofficial/how-recyclerview-works-internally-71290de5d2c4)
- [How to Cook the 60 FPS RecyclerView?](https://medium.com/rosberryapps/how-to-cook-the-60-fps-recyclerview-3e7f3885a55)
- [Smooth RecyclerView Scrolling in Android](https://medium.com/@polson55/smooth-recyclerview-scrolling-in-android-57e7a9b71ca7)
- [A guide to recyclerview-selection](https://proandroiddev.com/a-guide-to-recyclerview-selection-3ed9f2381504)
- [Smooth cross RecyclingViews Swipe](https://medium.com/mobile-app-development-publication/smooth-cross-recyclingviews-swipe-cc2810e13e0a)
- [Add extra depth to your list using parallax](https://medium.com/@patrick.elmquist/add-extra-depth-to-your-list-using-parallax-eddb27b369de)
- [Update recycler view content without refreshing the data](https://medium.com/@MiguelSesma/update-recycler-view-content-without-refreshing-the-data-bb79d768bde8)
- [Fast Scrolling with RecyclerView](https://android.jlelse.eu/fast-scrolling-with-recyclerview-2b89d4574688)
- [RecyclerView Anti-Patterns](https://proandroiddev.com/recyclerview-antipatterns-8af3feeeccc7)
 
### Adapter

- [Concatenate adapters sequentially with ConcatAdapter](https://medium.com/androiddevelopers/merge-adapters-sequentially-with-mergeadapter-294d2942127a)
- [Declarative Adapter Building](https://proandroiddev.com/declarative-adapter-building-91888f23b979)
- [Recycler view, power of asynchronous view holders creation](https://medium.com/@icesrgt/recycler-view-power-of-asynchronous-view-holders-creation-b3c9fe067702)

### ItemDecoration

- [ItemDecoration in Android](https://proandroiddev.com/itemdecoration-in-android-e18a0692d848)
- [Custom ItemDecoration](https://medium.com/@nicolas.duponchel/custom-itemdecoration-3b244de437d9)

### SnapHelper

- [Detecting snap changes with Android’s RecyclerView SnapHelper](https://medium.com/over-engineering/detecting-snap-changes-with-androids-recyclerview-snaphelper-9e9f5e95c424)
- [Inside RecyclerView’s SnapHelper](https://proandroiddev.com/android-recyclerview-snaphelper-19eaa9598da6)
- [Improving scrolling behavior of nested RecyclerViews - Part 1](https://rubensousa.com/2019/08/16/nested_recyclerview_part1/)

### LayoutManager

- [10 steps to create a custom LayoutManager](https://medium.com/android-development-by-danylo/10-steps-to-create-a-custom-layoutmanager-2f30ab2f979d)
- [Reel Search and LayoutManager: An Android journey](https://blog.usejournal.com/reel-search-and-layoutmanager-an-android-journey-e2f925c8410f)
- [RecyclerView animated transition between Grid and List layouts](https://medium.com/xorum-io/android-recyclerview-animated-transition-between-grid-and-list-layouts-b2309e1d9f19)
- [Building a RecyclerView LayoutManager – Part 1](https://wiresareobsolete.com/2014/09/building-a-recyclerview-layoutmanager-part-1)
- [Building a RecyclerView LayoutManager – Part 2](https://wiresareobsolete.com/2014/09/recyclerview-layoutmanager-2)
- [Building a RecyclerView LayoutManager – Part 3](https://wiresareobsolete.com/2015/02/recyclerview-layoutmanager-3)
- [Mastering RecyclerView Layouts](https://speakerdeck.com/devunwired/mastering-recyclerview-layouts)

### DiffUtil

- [Asynchronous DiffUtil with Kotlin Coroutines](https://proandroiddev.com/better-recyclerview-with-asynchronous-diffutil-and-kotlin-coroutines-f67e4f366cda)
- [RecyclerView — time to animate](https://blog.undabot.com/recyclerview-time-to-animate-with-payloads-and-diffutil-4278beb8d4dd)
- [DiffUtil is a must!](https://proandroiddev.com/diffutil-is-a-must-797502bc1149#.o2rfpnj0g)

### State Restoration

- [Restore RecyclerView scroll position](https://medium.com/androiddevelopers/restore-recyclerview-scroll-position-a8fbdc9a9334)
- [Saving scroll state of nested RecyclerViews - Part 2](https://rubensousa.com/2019/08/27/saving_scroll_state_of_nested_recyclerviews/)

### Animations

- [Enter animation using RecyclerView and LayoutAnimation Part 1: Lists](https://proandroiddev.com/enter-animation-using-recyclerview-and-layoutanimation-part-1-list-75a874a5d213)
- [Enter animation using RecyclerView and LayoutAnimation Part 2: Grids](https://proandroiddev.com/enter-animation-using-recyclerview-and-layoutanimation-part-2-grids-688829b1d29b)
- [Bounce effect in RecyclerView](https://medium.com/mindorks/bounce-effect-in-recyclerview-6463a7f81e5)
