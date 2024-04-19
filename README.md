## Solution Explained

In this FlexSim model, I used a date-time source (Source - Orders) to generate demand for each SCs (queues). Afterwards, I  data from each milestone such as how long it takes a particularly processor to reach the respective SC.
 
For example, if a particular item is unavailable then an item is created in Queue5 and sent to respective SC, the model will track time from order creation (demand generated in Source - Orders) to order delivery (reach at SC). It does not track the total time in the system because the part may have already existed before the demand was generated. I did this also because the processing times vary via distributions. The dashboard illustrates how I was able to do this for all compiled SC to track order to delivery time.
</br></br>

## 3D Animation 

https://github.com/GoodbyeKittyy/Order-Creation-to-Delivery-KPI-Simulation/assets/161730857/c6cdbde7-3acf-4200-810c-d4df6a017c41

</br></br>

## Live Process Flowchart

https://github.com/GoodbyeKittyy/Order-Creation-to-Delivery-KPI-Simulation/assets/161730857/ffab4899-2bb3-4309-ad72-773283bd3f53

</br></br>

## Live Dashboard

https://github.com/GoodbyeKittyy/Order-Creation-to-Delivery-KPI-Simulation/assets/161730857/f04d6d4c-2cc8-46c1-9c0a-4a13f7eb6067


