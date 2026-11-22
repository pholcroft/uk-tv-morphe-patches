# UK TV Patches

## Get the right Android TV APK first

The current patch requires **BBC iPlayer for Android TV 1.0.1 (build 101)**. This build is hard to find through ordinary APK searches. The phone app shares the same package name, and search results can also lead to older TV builds.

Use **Aurora Store in Anonymous mode** with our **Google TV Streamer (kirkwood)** profile. The walkthrough shows how to open the correct listing, check the build number, and save the APK for Morphe. [Watch the Aurora Store walkthrough](https://github.com/pholcroft/morphe-androidtv-patches/blob/feat/bbc-iplayer-1.0.1-preview/docs/bbc-iplayer/walkthroughs/README.md)

## Add the source to Morphe

[Add UK TV Patches to Morphe](https://morphe.software/add-source?github=pholcroft/uk-tv-morphe-patches&name=UK%20TV%20Patches)

Open the link on your Android phone with Morphe Manager installed, then tap **Open in Morphe → Add**.

If you started in Morphe, go to **Sources → UK TV Patches → Version** and tap **Watch the Aurora Store walkthrough** in the source notes.

This independent compatibility source is for use in the UK. Normal sign-in, geographic checks and DRM still apply.

This repository distributes the [compatibility patch source](src/StreamerCompatibilityPatch.kt) and the compiled Morphe patch. Obtain the original app separately. The [Android TV fork](https://github.com/pholcroft/morphe-androidtv-patches/tree/acc875bc9ec0371f4eb1fd42bf8eed597f805781) includes the original build configuration.
