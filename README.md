# Chat-Bot
A chatbot is your customer service support system. Using artificial intelligence and natural language processing, your chatbot can simulate the conversation with the user through messaging applications, websites, mobile applications, etc., providing them with accurate and appropriate information. By providing Watson Assistant support for the AI chatbot.

## How-to-Create-a-Chatbot-by-Watson-Assistant
Follow the steps shown in the link https://cloud.ibm.com/docs/assistant?topic=assistant-gs-dialog#getting-started-create-assistant

## code:

<script> 

  window.watsonAssistantChatOptions = {
  
    integrationID: "a5c2241e-2ecc-4bdf-9396-bcb32b842c71", // The ID of this integration.
    
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

## Result:
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠١-٢٤ في ٢ ٥٢ ٢٦ م" src="https://user-images.githubusercontent.com/108236976/185915231-c23c5e3e-e618-41d9-8e1f-6165c52ebbb1.png">
<img width="1440" alt="‏لقطة الشاشة ١٤٤٤-٠١-٢٤ في ٣ ٠٣ ٤٩ م" src="https://user-images.githubusercontent.com/108236976/185916927-ef94f0aa-41c0-4d14-b259-72fdbad4d645.png">

