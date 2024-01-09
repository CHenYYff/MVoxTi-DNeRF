# MVoxTi-DNeRF

<img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/b43cdb60-966c-4829-b853-6bbd2e83cd88.gif" width="10%"/><img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/469e5ad6-600f-4f22-bc4b-68c4aaeb64b3.gif" width="10%"/> <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/a7b807d7-e10a-4c78-8f96-a9daab4952cb.gif" width="10%"/> <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/442f3e84-3426-4aef-af13-528a4ac50bde.gif" width="10%"/> <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/e725423f-e075-4e9a-9b2d-10e03fa4c9e8.gif" width="10%"/> <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/1e2ac440-1e1e-409e-bb14-e564e0b3ccad.gif" width="10%"/> <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/1b42958f-2162-4412-9ca4-911ff4bcfbb4.gif" width="10%"/>  <img src="https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/cb1d67ce-ee0d-4a11-af26-d174357dec6d.gif" width="10%"/> 

https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/78cf2773-aacd-47a0-9a8c-e2ab8c559fb0


https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/5778cd61-2e3b-4cca-8330-3c9df91e7eda

https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/2652d094-b785-43d4-8dbb-7e3ba45e03df

https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/8ee14ae4-2ddc-440d-b927-f3ccab3c7ede

https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/b7569977-e796-47a1-9910-42917cfc1e0c



https://github.com/CHenYYff/MVoxTi-DNeRF/assets/117790613/d68d1f44-3379-4ebb-a10c-4180883c8c8e




<html><head lang="en"><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <title>D^2NeRF</title>

    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta property="og:image" content="https://d2nerf.github.io/img/title_card.png">
    <meta property="og:image:type" content="image/png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://github.com/d2nerf/d2nerf">
    <meta property="og:title" content="D^2NeRF: Self-Supervised Decoupling of Dynamic and Static Objects from a Monocular Video">
    <meta property="og:description" content="Given a monocular video, segmenting and decoupling dynamic objects while recovering the static environment is a widely studied problem in machine intelligence. Existing solutions usually approach this problem in the image domain, limiting their performance and understanding of the environment. We introduce Decoupled Dynamic Neural Radiance Field (D^2NeRF), a self-supervised approach that takes a monocular video and learns a 3D scene representation which decouples moving objects, including their shadows, from the static background. Our method represents the moving objects and the static background by two separate neural radiance fields with only one allowing for temporal changes. A naive implementation of this approach leads to the dynamic component taking over the static one as the representation of the former is inherently more general and prone to overfitting. To this end, we propose a novel loss to promote correct separation of phenomena. We further propose a shadow field network to detect and decouple dynamically moving shadows. We introduce a new dataset containing various dynamic objects and shadows and demonstrate that our method can achieve better performance than state-of-the-art approaches in decoupling dynamic and static 3D objects, occlusion and shadow removal, and image segmentation for moving objects.">

    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="D^2NeRF: Self-Supervised Decoupling of Dynamic and Static Objects from a Monocular Video">
    <meta name="twitter:description" content="Given a monocular video, segmenting and decoupling dynamic objects while recovering the static environment is a widely studied problem in machine intelligence. Existing solutions usually approach this problem in the image domain, limiting their performance and understanding of the environment. We introduce Decoupled Dynamic Neural Radiance Field (D^2NeRF), a self-supervised approach that takes a monocular video and learns a 3D scene representation which decouples moving objects, including their shadows, from the static background. Our method represents the moving objects and the static background by two separate neural radiance fields with only one allowing for temporal changes. A naive implementation of this approach leads to the dynamic component taking over the static one as the representation of the former is inherently more general and prone to overfitting. To this end, we propose a novel loss to promote correct separation of phenomena. We further propose a shadow field network to detect and decouple dynamically moving shadows. We introduce a new dataset containing various dynamic objects and shadows and demonstrate that our method can achieve better performance than state-of-the-art approaches in decoupling dynamic and static 3D objects, occlusion and shadow removal, and image segmentation for moving objects.">
    <meta name="twitter:image" content="https://d2nerf.github.io/img/title_card.png">


    <!-- mirror: F0%9F%AA%9E&lt -->
    <link rel="icon" href="data:image/svg+xml,&lt;svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22&gt;&lt;text y=%22.9em%22 font-size=%2290%22&gt;%E2%9C%A8&lt;/text&gt;&lt;/svg&gt;">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/codemirror.min.css">
    <link rel="stylesheet" href="css/app.css">

    <script src="js/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/codemirror.min.js"></script>
    <script src="js/clipboard.min.js"></script>
    <script src="js/video_comparison.js"></script>
    <script src="js/app.js"></script>
</head>
