# Flutter_Carosel

A simple Carousel Widget with multiple configuration option.

```yaml
...
dependencies:
 ...
 flutter_carousel: ^0.1.0
...
```

And install it using `flutter packages get` on your project folder. After that, just import the module and use it:

```dart
import 'package:carousel/carousel.dart';
//...
// make  a list of assets you want show in carousel
 List<String> assetList = ['assets/1.jpeg','assets/2.jpeg','assets/3.jpeg','assets/4.jpeg',
 'assets/5.jpeg','assets/6.jpeg','assets/7.jpeg'];

//...

Carousel(
    height: 350.0,
    width: 350,
    type: "simple",
    indicatorType: "bubble",
    arrowColor: Colors.white,
    axis: axis,
    showArrow: true,
    children: List.generate(
        7,
         (i) => Center(
            child: Container(
            color:Colors.red
            ),)))),

```

## Getting Startedslide

<table style="width:100%">
    <tr>
        <th>Properties</th>
        <th>Type</th>
        <th>Default Value</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>height</td>
        <td>Double</td>
        <td>null</td>
        <td>Defines height of carousel.This field is required</td>
    </tr>
    <tr>
        <td>width</td>
        <td>Double</td>
        <td>null</td>
        <td>Defines width of carousel. This field is required</td>
    </tr>
     <tr>
        <td>axis</td>
        <td>Axis</td>
        <td>Axis.horizontal</td>
        <td>Defines axis of carousel.</td>
    </tr>
    <tr>
        <td>type</td>
        <td>String</td>
        <td>"simple"</td>
        <td>Defines type of carousel. This field is required<br> Available carousel types are: "simple", "slideswiper",
            "bubble", "xrotating",
            "yrotating", "zrotating", "multirotating"</br></td>
    </tr>
    <tr>
        <td>showArrow</td>
        <td>Bool</td>
        <td>true</td>
        <td>choice to show arrow in carousel</td>
    </tr>
    <tr>
        <td>arrowColor</td>
        <td>Color</td>
        <td>Colors.white</td>
        <td>Define the color of arrow</td>
    </tr>
    <tr>
        <td>showIndicator</td>
        <td>Bool</td>
        <td>true</td>
        <td>Choice to show indicator in carousel</td>
    </tr>
    <tr>
        <td>indicatorType</td>
        <td>String</td>
        <td>bar</td>
        <td>Defines the type of indicator.<br> Available indicator types are: "bar", "dot", "bubble"</br></td>
    </tr>
    <tr>
        <td>activeIndicatorColor</td>
        <td>Color</td>
        <td>Colors.white</td>
        <td>Defines the color of active indicator</td>
    </tr>
    <tr>
        <td>unActiveIndicatorColor</td>
        <td>Color</td>
        <td>Colors.black</td>
        <td>Defines the color of unactive indicator</td>
    </tr>
    <tr>
        <td>indicatorBackgroundColor</td>
        <td>Color</td>
        <td>Color(0xff121212)</td>
        <td>Defines the background color of indicator</td>
    </tr>
    <tr>
        <td>indicatorBackgroundOpacity</td>
        <td>Double</td>
        <td>0.5</td>
        <td>Defines the opacity of indicator background</td>
    </tr>
</table>
<br></br>
![](https://github.com/GeekyAnts/flutter-carousel/blob/master/gifs/simple_carousel.gif) | ![](https://github.com/GeekyAnts/flutter-carousel/blob/master/gifs/simple_carousel.gif)

  <!-- <table style="width:100%">
       <tr>
            <td><img src="gifs/simple_carousel.gif"  height="450" /></td>
            <td><img src="gifs/slide_swipe.gif"  height="450" /></td>
            <td><img src="gifs/x_rotating.gif"  height="450" /></td>
        </tr>
      <tr>
            <td><img src="gifs/y_rotating.gif"  height="450" /></td>
            <td><img src="gifs/z_rotating.gif"  height="450" /></td>
            <td><img src="gifs/multi_rotating.gif"  height="450" /></td>
        </tr>
    </table> -->

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).
