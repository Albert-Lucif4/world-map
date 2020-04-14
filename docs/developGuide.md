the nCoV-map project Front-end development guide

Technology Stack
vue family bucket

mapv

Openlayers

()

Mapbox

Echarts

Late adoption
Cesium

Development environment
node s s 10

Development contract

### 1. Feature development
All in the 'src/views/' directory, the modules are reserved for everyone.

### 2. Front-end interface
All unified in the 'src/api/' directory management, it is recommended that a functional module interface are placed in the same interface file, interface files have been reserved for everyone.
Use the 'situation' module.

### 3. State management
Are unified in the 'src/store/' directory, suggesting that the status of a functional module be placed in a stand-alone file of 'src/store/modules/'. Then introduce it in 'src/store/index.js'.

