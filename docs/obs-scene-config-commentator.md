Purpose:

- Platform camera
- Competitor stats
- Sponsor logos

## Scene
<style>
table, th, td {
  border: 1px solid black;
}
</style>
|  <div style="width:500px">Step</div>                       |             OBS ScreenShot                |
|:-----------------------------------------------------------|:-----------------------------------------:|
| Scene :material-arrow-right: :heavy_plus_sign: (Add Scene) | ![](artifacts/scenes/new-scene.png)       |
| Name the Scene <br><b>Alternate - Commentator</b>          | ![](artifacts/scenes/commentator/co-scene-name.png)  |


## Groups

- Begin by creating all the groups required
- If you have already created some of these groups in other Scenes, you will just use the existing group, which will have the existing sources applied (although not all transforms or filters)
- `Main Platform Video Alternate` Group is **different** to the `Main Platform Video` Group, as there are border filters applied which we don't want on the main broadcast


| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| Sources :material-arrow-right: :heavy_plus_sign:  (Add Source)    | ![](artifacts/scenes/new-sources.png)                            |
| Create Groups                                                     | ![](artifacts/scenes/sources-new-group.png)                      |
| Add the *existing* Groups in order <b><br><ul>  <li>Flows</li><li>SponsorsBottomLeft</li><li>SponsorsTopLeft</li><li>LiftingCast-PlatformR</li><li>LiftingCast-PlatformL</li><li>Main Platform Video Alternative</li><li>Cam1Group</li><li>Logo</li></ul></b><br>Note: these will appear in *reverse* order | ![](artifacts/scenes/general-group-existing.png) |
| Completed Sources *Group* List and Ordering                       |![](artifacts/scenes/commentator/co-group-list.png) |

<hr style="border:2px solid black">


## Sources

- If you have already created some of these groups or sources in other Scenes, you will just use the existing source

### LiftingCast-PlatformR

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| `LiftingCast Platform Right` <br> Contains the following Sources set to the bottom-right of the Scene<br><br>**Note:**Before [Transforms](#transforms) and [Filters](#filters) have been applied, the items will be stacked in their default positions |  ![](artifacts/scenes/main-platform/mp-liftingcast-platformr.png) |
| **1920x2160 (Half-Width 4k)**<br>Use the existing source | ![](artifacts/scenes/sources-new-image.png)![](artifacts/scenes/main-platform/mp-source-add-existing-bg.png)  |
| **LiveFeed V3 Stats**<br>Use the existing source  | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-stats.png)  |
| **LiveFeed V1 Lights**<br>Use the existing source | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-lights.png)  |

<hr style="border:2px solid black">

### LiftingCast-PlatformL

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                            |
|:------------------------------------------------------------------|:----------------------------------------------------------------:|
| `LiftingCast Platform Left` <br> Contains the following Sources set to the bottom-left of the Scene<br><br>**Note:**Before [Transforms](#transforms) and [Filters](#filters) have been applied, the items will be stacked in their default positions |  ![](artifacts/scenes/main-platform/mp-liftingcast-platforml.png) |
| **1920x2160 (Half-Width 4k)**<br>Use the existing source | ![](artifacts/scenes/sources-new-image.png)![](artifacts/scenes/main-platform/mp-source-add-existing-bg.png)  |
| **LiveFeed V3 Stats**<br>Use the existing source  | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-stats.png)  |
| **LiveFeed V1 Lights**<br>Use the existing source | ![](artifacts/scenes/sources-new-browser.png)![](artifacts/scenes/main-platform/mp-source-add-existing-lights.png)  |

<hr style="border:2px solid black">


### Competiton Logo
This Image will generally change every competiton, and may require various versions added to OBS as different image sources:

 - to suit the placement
 - with or without transparent backgrounds 
 - various colour schemes

Use the Affinity products to modify a logo that may not quite suite the broadcast<br>
As a general guide, for logo design, consider the following
 
- ✅ Square, Oval, Circle, Triangle type logos generally work best where the Height:Width dimensions are **1:1**
- ✅ Logos that look good with Transparency and multiple different background colours also work
- 🚫 a large amount of black background do not work
    - they become washed out against other lighter or moving backgrounds
- 🚫 share a colour with another element of the logo (ie outer black background + inner black background wording)
    - The software can only mask on a colour, not parts of a logo without time consuming edits

- ✅ Parts of thick line-art (ie comic book style) or shadowing etc
    - ✅ Using a slightly different 'black' (ie #010101 vs #000000 ) where it is required

You may require a slightly different logo for the broadcast compared to the physical versions present on t-shits, posters, facebook etc

General steps to add an image in OBS as a Source, you can add as many as required

| <div style="width:500px">Step</div>                               |        OBS Screenshot                                                        |
|:------------------------------------------------------------------|:----------------------------------------------------------------------------:|
|  Sources → Add Source → Image          | ![](artifacts/scenes/new-sources.png)<br>![](artifacts/scenes/sources-new-image.png)                    |
|  Name the Source (CompLogo or similar) | ![](artifacts/scenes/slap-cam/sc-source-complogo.png)                                                   |
|  Choose the relevant Logo              | ![](artifacts/scenes/onedrive-complogo.png)                                                             |
|  Move the Source into the Logo Group   | ![](artifacts/scenes/slap-cam/sc-source-move.png)<br>![](artifacts/scenes/slap-cam/sc-source-moved.png) |
|  Hide the Source and Group until it's ready for transforms and filters to be applied | ![](artifacts/scenes/slap-cam/sc-source-logo-hide.png)                    |

<hr style="border:2px solid black">


## Transforms

## Filters

## Transitions
