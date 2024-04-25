Kino TEST


```
{
  "name": "Keijiro",
  "url": "https://registry.npmjs.com",
  "scopes": [ "jp.keijiro" ]
}
```

To the `dependencies` section:

```
"jp.keijiro.kino.post-processing": "2.1.15"
```

After changes, the manifest file should look like below:

```
{
  "scopedRegistries": [
    {
      "name": "Keijiro",
      "url": "https://registry.npmjs.com",
      "scopes": [ "jp.keijiro" ]
    }
  ],
  "dependencies": {
    "jp.keijiro.kino.post-processing": "2.1.15",
    ...
```

[scoped registry]: https://docs.unity3d.com/Manual/upm-scoped.html

Frequently Asked Questions
--------------------------

#### Nothing happens when I add effects to a volume

Check the Default HDRP Settings in the Project Settings. You have to
define custom post processing orders to make them take effect in the
pipeline.

![HDRP settings](https://i.imgur.com/v6Kddthl.jpg)

License
-------

[Unlicense](https://unlicense.org/)
