# **Magento 2 SagePay Integration**

Integrating SagePay with Magento 2 ensures secure, seamless, and efficient payment processing for your online store. SagePay, now known as Opayo, is a trusted payment gateway offering robust payment solutions. **Magento 2 SagePay Integration** facilitates multi-channel payments, enhances customer trust, and streamlines payment management for merchants.

## **How It Works**

**Magento 2 Opayo Payments** connects your store with the SagePay (Opayo) payment gateway. It enables secure transaction handling by redirecting customers to SagePay’s payment environment or processing payments directly on your site via the API. This integration supports multiple payment methods, including debit cards, credit cards and alternative payments like PayPal.

## **Key Features**

* Seamless integration with Sage Pay Payment Gateway  
* Accepting secured payments from customers  
* Magento 2 Opayo Form Integration  
* Magento 2 Opayo Direct Integration types

## **Seamless Checkout Experience**

hosted integration redirects customers to SagePay’s secure payment page, while direct integration enables payments directly within your Magento 2 store for an uninterrupted shopping experience.

## **Multi-Currency and Multi-Language Support**

supports multi-currency payments to make your store globally accessible and displays payment information in various languages for an enhanced customer experience.

## **Advanced Fraud Detection**

Magento 2 SagePay Integration features advanced fraud detection with AVS (Address Verification System), CV2 checks and 3D Secure authentication to minimize fraudulent transactions.

## **Customizable Payment Pages**

It allows merchants to design SagePay-hosted payment pages that align with their brand while offering a responsive design optimized for both desktop and mobile users.

## **Simplified Refund Management**

It simplifies refund management by allowing merchants to issue full or partial refunds directly from the Magento admin panel while maintaining a detailed history of all transactions and refunds for easy tracking.

## **Extension Installation**

To install the **Magento 2 Sage Pay Integration**  extension:

### **Step 1:**

Extract the zip folder and upload our extension to the root of your Magento 2 directory via FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Integrate SagePay with Magento 2**

To integrate SagePay with Magento 2, follow these steps:

### **Step 1: Enable the extension**

* Log in to the Magento admin panel.  
* Go to **Stores \> Configuration \> Sales \> Payment Methods**.

### **Step 2: Configure SagePay Integration**

![Configure SagePay Integration](https://github.com/user-attachments/assets/01bce9bb-1e7d-4715-bc83-756e96055beb)

* **Enable the Payment Method**: Set **Enabled** to “Yes” to activate the payment method.  
* **Set the Payment Title**:Define the **Title** to display for the payment method on the frontend.  
* **Enable Sandbox Mode**: Set **Sandbox Mode** to “Yes” for testing purposes.  
* **Vendor Name :** Add the **Vendor Name** provided during registration with Sage Pay Gateway.  
* **Form Integration Encryption Password:** Enter the **Form Integration Encryption Password**, obtained from Sage Pay during registration.

![Configure SagePay](https://github.com/user-attachments/assets/c3601cc9-8d4a-4b16-9a08-430c6db404f3)

* **Enable Gift Aid**: Gift Aid, available to UK taxpayers, increases the value of charity donations by 25%. Set this option to **Yes** to activate the feature.  
* **Verification Options**: Configure **Address Verification Status (AVS)** and **Card Verification Value (CVV)** to enhance payment security.  
* **Enable 3D Secure**: Activate 3D Secure to provide an additional layer of protection for online transactions.  
* **Custom Information**: Add HTML content to display additional details about the payment method on the cart page.  
* **Sort Order**: Define the order in which this payment method appears on the checkout page.

### **Step 3: Sage Pay Form Payments on the Frontend**

After configuring the extension, the Sage Pay Form payment method will be successfully enabled and available for use on the storefront.

* **Sage Pay Payment Method on the Cart Page**

![Sage Pay Payment Method on the Cart Page](https://github.com/user-attachments/assets/a34d5cac-4251-4ef3-ab89-c27239121bd2)

When customers add products to their cart, they can select the Sage Pay Form payment method. To proceed, they need to enter their credit card details and click the “Place Order” button, completing the payment and successfully placing the order.

![Sage Pay Payment with transaction details](https://github.com/user-attachments/assets/950545f2-8e7e-41c4-b7d3-3a1daff436a1)

* **Redirection to Sage Pay Gateway :** When customers click the "Continue to Payment" button on the cart page, they are redirected to the Sage Pay payment gateway to select their card type and complete the transaction.

![Redirection to Sage Pay Gateway](https://github.com/user-attachments/assets/7ac73d87-2d6a-43a6-a9aa-f49a9993eacd)

* **Enter Card Details:** After selecting the card type, customers are prompted to enter their card details to proceed with the payment.

![Enter Card Details](https://github.com/user-attachments/assets/83fa2d9f-6697-4c09-9761-d16cb6c50261)

* **Confirm Card Details :** After entering the card details, customers can review and confirm the information before proceeding to complete the payment.

![Confirm Card Details](https://github.com/user-attachments/assets/d8e1b410-f3c7-472e-b4ac-74e09e809cb5)

* **Sage Pay Payment Method in the My Account Section:** After an order is placed, customers can view all related order and payment details in the My Orders tab under the My Account section.

### **Step 4: Sage Pay Form Payments in the Backend**

![Sage Pay Form Payments in the Backend](https://github.com/user-attachments/assets/5dcc60cf-9176-4e06-b09f-061cc235860a)

* After an order is placed using the Sage Pay payment method, transaction details can be accessed in the backend within the order view section.

### **Step 5: Sage Pay Form Payment Details in Order Emails**

![Sage Pay Form Payment Details in Order Emails](https://github.com/user-attachments/assets/a4c55f95-ff14-4807-b385-bc177264bf47)

In addition to viewing in the backend, customers receive order and Sage Pay payment details through the order confirmation email.

## Download our [Magento 2 SagePay Integration](https://meetanshi.com/magento-2-sagepay-integration.html) Extension
