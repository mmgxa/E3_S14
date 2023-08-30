<div align="center">

# Session 14

</div>

In this session, we export a YOLOv8 (small) model to ONNX and deploy it in the browser. This is then hosted using a Next.js frontend on Vercel.


## Convert Model

To convert model, we run the file:

```
python convert_yolo_to_onnx.py 
```

This is then copied to the `{frontend_path}/public/model` directory.

