# MapEditor-Ionic4-inProgress

     frontend (Ionic):
     backend (PHP): https://github.com/ninabee94/MapEditor-API-PHP-inProgress

![alt](https://user-images.githubusercontent.com/57636419/69968834-3ba10300-1556-11ea-8bc4-80e0aa413a84.JPG)

<b>Dpendencies</b>

     npm install --save rxjs
     npm install --save rxjs-compat
     npm install --save @ionic-native/google-maps@5.5.0
     npm install --save @angular/http
     npm install @ionic-native/image-resizer
     ionic cordova plugin add https://github.com/mapsplugin/cordova-plugin-googlemaps#multiple_maps --variable API_KEY_FOR_ANDROID="AIzaSyBUqFl9FGqvYFIrVeVtPc21EtoEVkG5iic"
     ionic cordova plugin add info.protonet.imageresizer
     
<b>Edit app.module.ts</b>

     import { GoogleMaps } from '@ionic-native/google-maps/ngx';
     import { HttpModule } from '@angular/http';
     add imports: [httpmodule]
     add providers: [GoogleMaps,ImageResizer]
