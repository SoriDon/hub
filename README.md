## Ultralytics HUB

👋 Hello from the Ultralytics Team! We've been working hard these last few months to launch [Ultralytics HUB](https://ultralytics.com/hub), a new web tool for training and deploying all your YOLOv5 🚀 models from one spot!


## Dataset Guidelines

Ultralytics HUB datasets are just like YOLOv5 🚀 datasets, they use the same structure and the same label formats to keep everything simple. 

When you load a file to Ultralytics HUB, make sure to **place your dataset yaml inside the dataset root directory** as in the example shown below, and then zip for upload to https://hub.ultralytics.com/. Your **dataset yaml and directory** should also share the same name. For example, if your dataset is called coco6, then you should have a coco6.yaml inside your coco6/ directory, which should zip to create coco6.zip for upload:

```bash
zip -r coco6.zip coco6
```

The example [coco6.zip](https://github.com/ultralytics/hub/blob/master/coco6.zip) dataset in this repository can be downloaded and unzipped to see exactly how to structure your custom dataset.
<p align="center"><img width="800" src="https://user-images.githubusercontent.com/26833433/141502652-e4b0477c-6c2a-41b3-b21a-b3d1444cdda7.png" title="COCO6" /></p>

After zipping sign in to HUB at https://hub.ultralytics.com and click on the Datasets tab. Click 'Upload Dataset' to upload, scan and visualize your new dataset!

<img width="1200" alt="HUB Dataset Upload" src="https://user-images.githubusercontent.com/26833433/141504055-cf2cb4bf-6045-4957-bf23-d4d2c8a94fae.png">


## ❓ Issues

If you are a new Ultralytics HUB user and have questions or comments for Ultralytics, you are in the right place! Please click the [New Issue](https://github.com/ultralytics/hub/issues/new/choose) button in the [Issues](https://github.com/ultralytics/hub/issues) tab in this [ultralytics/hub](https://github.com/ultralytics/hub) repo and let us know what we can do to make your AI life better 😃!

<img width="930" alt="Screenshot 2021-11-12 at 16 42 41" src="https://user-images.githubusercontent.com/26833433/141493990-7cd392de-579a-42ab-8e3e-a0bfb44cd179.png">


<br>

<div align="center">
    <a href="https://github.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.linkedin.com/company/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://twitter.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-twitter.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://youtube.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-youtube.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.facebook.com/ultralytics">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-facebook.png" width="3%"/>
    </a>
    <img width="3%" />
    <a href="https://www.instagram.com/ultralytics/">
        <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-instagram.png" width="3%"/>
    </a>
</div>
