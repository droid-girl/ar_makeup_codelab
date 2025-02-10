# ARCore Try-on Makeup with Shaders

## Simple usage:

```
<fragment android:name="blog.creativetech.arfaces.arface.AugmentedFaceFragment"
       android:id="@+id/face_view"
       android:layout_width="match_parent"
       android:layout_height="match_parent"
       android:layout_gravity="top" />
```
Use `AugmentedFaceFragment` in your `main_activity` layout

Implement interface in MainActivity

```
class MainActivity : AppCompatActivity(), AugmentedFaceListener {
   override fun onFaceAdded(face: AugmentedFaceNode) {}

   override fun onFaceUpdate(face: AugmentedFaceNode) {}
}
```
Check out the new and updated repository -> [arfaces_labs](https://github.com/droid-girl/arfaces_labs)

<div align="left">
      <a href="https://www.youtube.com/watch?v=_xnUo4HL1QQ">
         <img src="https://img.youtube.com/vi/_xnUo4HL1QQ/0.jpg" style="width:100%;">
      </a>
</div>
