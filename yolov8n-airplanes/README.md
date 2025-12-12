# yolov8n tfjs airplane detection on sattellite images 
Yolov8n tfjs model trained on Airplanes Detection Dataset from Kaggler mrcsgh (from pytorch model).

## use tf.js

```<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs"></script>```

### Run prediction
```
<script>
async function loadModel() {
  const model = await tf.loadLayersModel(
    "https://cdn.jsdelivr.net/gh/<username>/<repo>/my-model/model.json"
  );
  console.log("Model loaded!", model);
}

loadModel();
</script>
```



