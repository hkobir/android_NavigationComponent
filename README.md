## android_NavigationComponent
Android, Navigation Components, Fragment, Nav_graph, Nav_host

## Step To setup Jeetpack Navigation Component
 - Define defendency: https://developer.android.com/guide/navigation/navigation-getting-started
 - Create a navigation graph: right-click on the res directory and select New > Android Resource File > Resource nam is "nav_graph" and type is Navigation
 - Add a NavHostFragment within main activity
 - create fragments as need for page
 - design destination baseed on nav_graph for all state of fragment

## Find Nav controller from any where for interaction 

  - NavHostFragment.findNavController(Fragment)
  - Navigation.findNavController(Activity, @IdRes int viewId)
  - Navigation.findNavController(View)



## Clear concept about this:
https://codelabs.developers.google.com/codelabs/android-navigation/index.html?index=..%2F..%2Findex#0

