# Chat-Bot
A chatbot is your customer service support system. Using artificial intelligence and natural language processing, your chatbot can simulate the conversation with the user through messaging applications, websites, mobile applications, etc., providing them with accurate and appropriate information. By providing Watson Assistant support for the AI chatbot.

## How-to-Create-a-Chatbot-by-Watson-Assistant
Follow the steps shown in the link https://cloud.ibm.com/docs/assistant?topic=assistant-gs-dialog#getting-started-create-assistant

## code:
```json
<script> 

     window.watsonAssistantChatOptions = {
     
     integrationID: "3f428f72-4625-42b1-ab54-61bf7f66a979", // The ID of this integration.
                
     region: "eu-gb", // The region your integration is hosted in.
                
     serviceInstanceID: "6b1d0819-4ee1-4a4a-a183-cefffcfd9adc", // The ID of your service instance.
                
     onLoad: function(instance) { instance.render(); }
            };
            
     setTimeout(function(){
              
     const t=document.createElement('script');
              
     t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
              
     document.head.appendChild(t);
            });

</script>
```
## Result:
<img width="1438" alt="‏لقطة الشاشة ١٤٤٤-٠٢-٢٤ في ١١ ٤٥ ٤١ م" src="https://user-images.githubusercontent.com/108236976/191361356-730abee0-7fbf-48e3-9455-95a098b5d90f.png">

<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠٢-٢٤ في ١١ ٤٨ ٠٩ م" src="https://user-images.githubusercontent.com/108236976/191361456-81e22d7d-6bbd-43e0-ac01-4fe9e8a773b2.png">

