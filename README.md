# adapterPattern
<h3>Software Engineering 1 | Lab Assignment 3</h3>
<h3>Problem Statement:</h3>
You are developing an application that helps users manage and control various electronic devices by plugging them into power outlets. Each device has different plug types, voltage, and amperage requirements. To ensure compatibility and safety, you need to create adapters for different devices to allow them to be plugged into standard power outlets.<br><br>

<strong>○ Adaptee Objects:</strong>
<ul>
<li>Laptop - Represents a laptop device that needs to be plugged into a power source. It has the charge() method.</li><br>
<li>Refrigerator - Represents a refrigerator device that requires a power source. It has the startCooling() method.</li><br>
<li>SmartphoneCharger - Represents a smartphone charger that needs to be plugged in for charging. It has the chargePhone() method.</li><br>
</ul>

<strong>○ Target Object:</strong>
<ul>
<li>PowerOutlet - Represents a standard power outlet with a common interface for plugging in devices. It defines the plugIn() method as the target method.</li><br>
</ul>

<strong>○ Adapter Objects:</strong>
<ul>
<li>LaptopAdapter - An adapter for plugging a laptop into a standard power outlet. It adapts the Laptop to the PowerOutlet interface, translating plugIn() to charge().</li><br>
<li>RefrigeratorAdapter - An adapter for plugging a refrigerator into a standard power outlet. It adapts the Refrigerator to the PowerOutlet interface, translating plugIn() to startCooling().</li><br>
<li>SmartphoneAdapter - An adapter for plugging a smartphone charger into a standard power outlet. It adapts the SmartphoneCharger to the PowerOutlet interface, translating plugIn() to chargePhone().</li><br><br>
</ul>
<h3>UML Class Diagram:</h3>
<img width="2672" height="1637" alt="POAS_UML" src="https://github.com/user-attachments/assets/ff7b35a1-2847-402a-86a9-f9d9e72ee05b" />
