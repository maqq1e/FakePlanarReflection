# Fake Planar Reflection - URP

![Edge Fade demonstration](https://i.imgur.com/QOxuUy4.png)

Simple shader for URP Unity projects based on fake interior shader. 

# Download

```sh
git clone https://github.com/maqq1e/FakePlanarReflection.git
```

**OR**

[GO ON RELEASES](https://github.com/maqq1e/FakePlanarReflection/releases)

# Features

#### *Tint Reflection*

![Tint demonstration](https://i.imgur.com/HzzBapG.gif)

Easy to change color of reflection.

#### *Refraction Intensity*

![Refraction demonstration](https://i.imgur.com/KHBPv01.gif)

Normal map can be use for make distortion on reflection.

#### *Edge Fade Opacity Intensity*

![Edge Fade demonstration](https://i.imgur.com/AlfY9Ls.gif)

Can increase or decrease edge fade opacity. It's make transition between decal and floor surface more smooth. 

#### *Opacity Mask Control*

![Opacity Mask demonstration](https://i.imgur.com/dffJUSm.gif)

Using some grunge mask you can make reflection much more rough.

#### *Realtime Reflection by Render Texture*

![Realtime Reflection demonstration](https://i.imgur.com/GZS3o5i.gif)

With using camera close to wall and output it into rendet texture, you can achieve realtime reflection.

#### *Render Texture to Texture2D*

![Render Texture to Texture2D demonstration](https://i.imgur.com/xnseyeO.png)

If you don't want to use real time reflection you can convert your Rendert Texture into Texture2D by using [this script](https://github.com/maqq1e/FakePlanarReflection/blob/main/Assets/Editor/CS_SaveRenderTexture.cs). It's include into this project.

> Hope this shader will be usefull for anyone. I will be glad to see your ideas how to improve this shader.

# Aditional Sources:
- [**Save Render Texture to Texture2D script**]( https://gist.github.com/krzys-h/76c518be0516fb1e94c7efbdcd028830)
- [**Bricks Wall Textures CC0**](https://ambientcg.com/view?id=PavingStones122)
- [**Marble Floor Textures CC0**](https://ambientcg.com/view?id=Marble016)
- [**Metal Tile Textures CC0**](https://ambientcg.com/view?id=MetalPlates006)
