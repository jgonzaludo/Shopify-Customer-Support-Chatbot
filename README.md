
# Shopify Customer Support Chatbot

The Shopify Customer Service Chatbot is a powerful tool designed to enhance the shopping experience by providing real-time assistance to customers. This chatbot is integrated directly into your Shopify store, allowing customers to easily track orders, manage returns, and access comprehensive company information and policies.





## Internal Use Only

This chatbot is intended to be managed and edited exclusively by internal personnel at The Barrax Company. All configurations, updates, and maintenance should be performed by authorized staff to ensure consistency and security.
## Features

**Order Tracking**

- Real-Time Updates: Customers can track their order status and fulfillment process in real-time.\
- Shipping Notifications: Receive updates on shipping and delivery statuses directly through the chatbot.

**Returns Management**

- Initiate Returns: Customers can easily initiate the return process for their orders.\
- Return Status: Track the status of returns and refunds seamlessly.\
**Comprehensive Information Access** 

- Company Policies: Read all company policies including:
  - Return Policy
  - Shipping Policy
  - Terms of Service
  - Privacy Policy
- Product Information: Access detailed product descriptions, uses, and prices.
- Product Suggestions: Receive personalized product recommendations based on browsing and purchase history.
## Benefits

- Enhanced Customer Experience: Provide instant support and information to customers, improving satisfaction and loyalty.
- Streamlined Operations: Automate routine inquiries and processes, freeing up your customer service team for more complex issues.
- Increased Engagement: Keep customers engaged with personalized recommendations and timely updates.
## Usage

Customers can interact with the chatbot by clicking on the chat icon on your Shopify store. They can ask questions, track their orders, initiate returns, and access various policies and product information. The chatbot is designed to provide quick and accurate responses, ensuring a smooth and efficient customer service experience.


## Deployment

To deploy this project run, integrate the chatbot into your Shopify store by adding the provided custom HTML and CSS code.

```bash
  <script type="text/javascript">
  (function(d, t) {
      var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
      v.onload = function() {
        window.voiceflow.chat.load({
          verify: { projectID: 'HIDDEN' },
          url: 'https://general-runtime.voiceflow.com',
          versionID: 'production'
        });
      }
      v.src = "https://cdn.voiceflow.com/widget/bundle.mjs"; v.type = "text/javascript"; s.parentNode.insertBefore(v, s);
  })(document, 'script');
</script>
```
Configure Settings: Customize the chatbot settings to match your store’s needs and branding.

Activate: Once configured, activate the chatbot to start assisting your customers.

## Support

For any issues or assistance with the chatbot, please contact me at josephgonzaludo27@gmail.com.


## Authors

- [Joseph Gonzaludo](https://www.github.com/jgonzaludo)


## License

[MIT](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License. See the LICENSE file for more details.