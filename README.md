# my_project_package
Exercici d'integració 3.1

Els arguments del node `usb_cam-test.launch` són els següents:

Per començar el *launch* llança 2 nodes:
- usb_cam
- image_view

Els paràmetres de usb_cam són:
- **video_device**: On es diu quin *device* és la càmera de video. El valor per defecte és:"/dev/video0".
- **image_width**: Amplada de la imatge. El valor per defecte és: "640".
- **image_height**: Alçada de la imatge. El valor per defecte és: "480".
- **pixel_format**: Format dels píxels. Els valors possibles d'aquest paràmetre són: mjpeg, yuyv, uyvy. Per defecte el "yuyv".
- **camera_frame_id**: És un *string* que identifica la càmera "usb_cam".
- **io_method**: Mètode de sortida, possibles valors: mmap, read, userptr. El valor per defecte és:"mmap".

Els paràmetres de image_view són:
- **autosize**: On s'especifica que la grandaria de la finestra sigui automàtica. El valor per defecte és "true".

