# 🧠 n8n Workflow Collection

This repository contains **n8n workflows** collected from multiple sources, including:

- Workflows exported from the [n8n.io](https://n8n.io) website and community forums
- Examples shared publicly on the web (GitHub, blogs, etc.)

The goal is to provide useful inspiration, learning, and reusable resources for your n8n projects.

---

## 📂 Folder Structure

- Each `.json` file represents an exported workflow.
- Files are named according to the original title or source.
- You may also find some `.txt` files that have been converted to `.json` (see instructions below).

---

## 🔄 TXT to JSON Conversion

Some workflows are originally stored as `.txt` files or copied from online sources. Use the script to:

1. Detect `.txt` files  
2. Try to parse them as JSON or structured key-value pairs  
3. Convert them to valid `.json` format  

If you want to perform the conversion yourself, check out `convert_txt_to_json.py` included in this repository.

---

## 🛠 Instructions

To import a workflow into your own n8n instance:

1. Open your [n8n Editor UI](https://docs.n8n.io/hosting/editor-ui/).  
2. Click the **Menu** (☰) in the top right → **Import Workflow**.  
3. Select a `.json` file from this folder.  
4. Click **Import** to load the workflow.  

Before running, make sure to check and modify any required credentials or webhook URLs.

---

## 📋 Workflow List

Here are all the available workflows, grouped by category:

### 🤖 AI Agents and Chatbots

- [🤖 Telegram Text/Audio/Image Messaging Agent](workflows/🤖%20Telegram%20Messaging%20Agent%20for%20Text_Audio_Images.json)  
  *Telegram agent with multimedia support*

- [🤖🧑‍💻 n8n Creators Leaderboard AI Agent](workflows/🤖🧑_%E2%80%8D%20%F0%9F%92%BB%20AI%20Agent%20for%20Top%20n8n%20Creators%20Leaderboard%20Reporting.json)  
  *Top n8n Creators Leaderboard reporting*

- [🤖🧠 AI Chatbot + Long-term Memory + Note Storage + Telegram](workflows/🤖🧠%20AI%20Agent%20Chatbot%20+%20LONG%20TERM%20Memory%20+%20Note%20Storage%20+%20Telegram.json)  
  *Chatbot with long-term memory*

- [🐋🤖 DeepSeek AI Agent + Telegram + Long-term Memory 🧠](workflows/🐋🤖%20DeepSeek%20AI%20Agent%20+%20Telegram%20+%20LONG%20TERM%20Memory%20🧠.json)  
  *Intelligent agent based on DeepSeek*

- [🔐🦙🤖 Private Local Ollama AI Agent for n8n Creators Leaderboard – Find Popular Workflows](workflows/%F0%9F%94%90%F0%9F%A6%99%F0%9F%A4%96%20AI%20Agent%20for%20n8n%20Creators%20Leaderboard%20-%20Find%20Popular%20Workflows.json)  
  *Discover popular workflows*

- [🚀 Local Multi-LLM Testing and Performance Tracker](workflows/🚀%20Local%20Multi-LLM%20Testing%20&%20Performance%20Tracker.json)  
  *Multi-model performance comparison tool*

- [HR & IT Helpdesk Chatbot with Audio Transcription](workflows/zmgSshZ5xESr3ozl_HR_%26_IT_Helpdesk_Chatbot_with_Audio_Transcription.json)  
  *Enterprise helpdesk solution*

- [Travel Assistant Agent](workflows/znRwva47HzXesOYk_Travel_AssistantAgent.json)  
  *Smart travel planning assistant*

- [🐋 DeepSeek V3 Chat and R1 Reasoning Quick Start](workflows/🐋DeepSeek%20V3%20Chat%20&%20R1%20Reasoning%20Quick%20Start.json)  
  *DeepSeek V3 model usage guide*

- [Build a Custom AI Agent with LangChain and Gemini (Self-Hosted)](workflows/yCIEiv9QUHP8pNfR_Build_Custom_AI_Agent_with_LangChain_%26_Gemini_(Self-Hosted).json)  
  *Custom AI agent build guide*

- [AI Agent Chatbot with Jina.ai Webpage Scraper](workflows/xEij0kj2I1DHbL3I_%F0%9F%8C%90%F0%9F%A4%9B_AI_Agent_Chatbot_with_Jina.ai_Webpage_Scraper.json)  
  *Web content understanding chatbot*

- [WhatsApp AI Chatbot for Text, Voice, Images, and PDFs](workflows/zMtPPjJ80JJznrJP_AI-Powered_WhatsApp_Chatbot_for_Text%2C_Voice%2C_Images_%26_PDFs.json)  
  *Full-featured WhatsApp assistant*

- [Line Chatbot Handling AI Responses with Groq and Llama3](workflows/xibc6WDU53isYN1o_Line_Chatbot_Handling_AI_Responses_with_Groq_and_Llama3.json)  
  *Line platform chatbot*

- [Microsoft Outlook AI Email Assistant](workflows/reQhibpNwU63Y8sn_Microsoft_Outlook_AI_Email_Assistant.json)  
  *Intelligent email processing assistant*

- [Email AI Auto-Responder: Summarize and Send Email](workflows/q8IFGLeOCGSfoWZu_Email_AI_Auto-responder_Summarize_and_send_email.json)  
  *Smart email auto-reply*

- [Discord MCP Chat Agent](workflows/xRclXA5QzrT3c6U8_Discord_MCP_Chat_Agent.json)  
  *Discord chat bot*

- [HubSpot Chat Assistant using OpenAI and Airtable](workflows/vAssistant_%20for%20Hubspot%20Chat%20using%20OpenAi%20and%20Airtable.json)  
  *CRM integrated chat assistant*

### 📊 Content Creation and Analysis

- [📚 Auto-generate documentation for n8n workflows with GPT and Docsify](workflows/📚%20Auto-generate%20documentation%20for%20n8n%20workflows%20with%20GPT%20and%20Docsify.json)  
  *Automatic document generation*

- [🔍 Perplexity Research to HTML: AI-Powered Content Creation](workflows/🔍%20Perplexity%20Research%20to%20HTML_%20AI-Powered%20Content%20Creation.json)  
  *Research content conversion*

- [⚡ AI-Powered YouTube Video Summarization and Analysis](workflows/⚡AI-Powered%20YouTube%20Video%20Summarization%20&%20Analysis.json)  
  *Video content analysis*

- [🎨 Using FLUX.1 Interactive Image Editor with FLUX.1 Fill Tool for Inpainting](workflows/🎨%20Using%20FLUX.1%20Interactive%20Image%20Editor%20with%20FLUX.1%20Fill%20Tool%20for%20Inpainting.json)  
  *AI image editing*

- [Turn YouTube Videos into Summaries, Transcripts, and Visual Insights](workflows/Turn%20YouTube%20Videos%20into%20Summaries_%20Transcripts_%20and%20Visual%20Insights.json)  
  *Video content analysis*

- [YouTube Comment Sentiment Analyzer](workflows/YouTube%20Comment%20Sentiment%20Analyzer.json)  
  *Comment sentiment analysis*

- [WordPress Blog Post AI Auto-Tag](workflows/siXUnQhJpCJ9rHzu_Auto-Tag_Blog_Posts_in_WordPress_with_AI.json)  
  *Content tagging automation*

- [🎦💌 Advanced YouTube RSS Feed Buddy](workflows/tHgDFmFyuj6DnP6l_🎦💌Advanced_YouTube_RSS_Feed_Buddy_for_Your_Favorite_Channels.json)  
  *YouTube content tracking*

- [n8n Graphic Design Team](workflows/tnRYt0kDGMO9BBFd_n8n_Graphic_Design_Team.json)  
  *Design workflow*

- [Use Perplexity AI to Search News and Publish to X (Twitter)](workflows/v9K61fCQhrG6gt6Z_Search_news_using_Perplexity_AI_and_post_to_X_%28Twitter%29.json)  
  *News sharing automation*

- [Social Media Publisher](workflows/r1u4HOJu5j5sP27x_Social_Media_Publisher.json)  
  *Multi-platform content publishing*

- [Post to X](workflows/plzObaqgoEvV4UU0_Post_on_X.json)  
  *Twitter automated publishing*

- [YouTube Automation](workflows/wLbJ7rE6vQzizCp2_Youtube_Automation.json)  
  *YouTube content management*

### 🌐 Web Crawler and Data Extraction

- [✨ Visual-based AI Agent Crawler – with Google Sheets, ScrapingBee, and Gemini](workflows/✨%20Vision-Based%20AI%20Agent%20Scraper%20-%20with%20Google%20Sheets_%20ScrapingBee_%20and%20Gemini.json)  
  *Visual web scraper*

- [Intelligent Web Query and Semantic Re-Ranking Flow](workflows/wa2uEnSIowqSrHoY_Intelligent_Web_Query_and_Semantic_Re-Ranking_Flow.json)  
  *Intelligent search ranking*

- [Essential Multipage Website Scraper with Jina.ai](workflows/xEij0kj2I1DHbL3I_💡🌐_Essential_Multipage_Website_Scraper_with_Jina.ai.json)  
  *Multipage website scraping*

### 🕵️ Face Crawler

- [Scrape Trustpilot Reviews with DeepSeek, Analyze Sentiment with OpenAI](workflows/w434EiZ2z7klQAyp_Scrape_Trustpilot_Reviews_with_DeepSeek,_Analyze_Sentiment_with_OpenAI.json)  
  *Review sentiment analysis*

- [Extract and Summarize Wikipedia Data with Bright Data and Gemini AI](workflows/sczRNO4u1HYc5YV7_Extract_%26_Summarize_Wikipedia_Data_with_Bright_Data_and_Gemini_AI.json)  
  *Wikipedia content processing*

- [Generate Company Stories from LinkedIn with Bright Data and Google Gemini](workflows/q1DorytEoEw1QLGj_Generate_Company_Stories_from_LinkedIn_with_Bright_Data_%26_Google_Gemini.json)  
  *LinkedIn content analytics*

- [Brand Content Extraction, Summarization and Sentiment Analysis with Bright Data](workflows/wTI77cpLkbxsRQat_Brand_Content_Extract,_Summarize_%26_Sentiment_Analysis_with_Bright_Data.json)  
  *Brand content analysis*

- [News Extraction](workflows/xM8Z5vZVNTNjCySL_News_Extraction.json)  
  *News content crawler*

### 📱 Communications and Message Processing

- [WhatsApp Starter Workflow](workflows/yxv7OYbDEnqsqfa9_WhatsApp_starter_workflow.json)  
  *WhatsApp basic settings*

- [📈 Receive Daily Market News from FT.com to your Microsoft Outlook inbox](workflows/📈%20Receive%20Daily%20Market%20News%20from%20FT.com%20to%20your%20Microsoft%20outlook%20inbox.json)  
  *Market news push*

### 🗃️ Data Management and Synchronization

- [📦 New Email ➔ Create Google Task](workflows/z0C6H2kYSgML2dib_📦_New_Email_➔_Create_Google_Task.json)  
  *Email-to-task conversion*

- [Synchronize Google Sheets with Postgres](workflows/wDD4XugmHIvx3KMT_Synchronize_your_Google_Sheets_with_Postgres.json)  
  *Database synchronization*

- [Sync New Files from Google Drive to Airtable](workflows/uLHpFu2ndN6ZKClZ_Sync_New_Files_From_Google_Drive_with_Airtable.json)  
  *File management synchronization*

- [Sync YouTube Video URLs to Google Sheets](workflows/rJNvM4vU6SLUeC1d_Sync_Youtube_Video_Urls_with_Google_Sheets.json)  
  *Video list management*

- [Import CSV from URL to Excel](workflows/xcl8D1sukz9Rak69_Import_CSV_from_URL_to_Excel.json)  
  *Data import*

- [How to Automatically Import CSV Files into Postgres](workflows/q8GNbRhjQDwDpXoo_How_to_automatically_import_CSV_files_into_postgres.json)  
  *Database import*

- [Import Multiple Manufacturers from Google Sheets to Shopware 6](workflows/xLjE4IkQXARXOCZy_Import_multiple_Manufacturers_from_Google_Sheets_to_Shopware_6.json)  
  *E-commerce data import*

- [Import Multiple CSV to Google Sheet](workflows/zic2ZEHvxHR4UAYI_Import_multiple_CSV_to_GoogleSheet.json)  
  *Batch data import*

- [Update Roles by Excel](workflows/xzKlhjcc6QEzA98Z_Update_Roles_by_Excel.json)  
  *Permission management*

- [Zip Multiple Files](workflows/r3qHlCVCczqTw3pP_Zip_multiple_files.json)  
  *Archive packaging*

- [Merge Multiple Runs into One](workflows/ynTqojfUnGpG2rBP_Merge_multiple_runs_into_one.json)  
  *Merge execution results*

### 🏢 Enterprise and CRM Management

- [LinkedIn Automation](workflows/yF1HNe2ucaE81fNl_Linkedin_Automation.json)  
  *LinkedIn marketing automation*

- [Perform an Email Search with Icypeas (Single)](workflows/Perform%20an%20email%20search%20with%20Icypeas%20%28single%29.json)  
  *Email search*

- [Meeting Booked → Newsletter and CRM](workflows/xe9sXQUc7yW8P8im_Meeting_booked_-_to_newsletter_and_CRM.json)  
  *Meeting management integration*

- [ICP Company Scoring](workflows/xyLfWaqdIoZmbTfv_ICP_Company_Scoring.json)  
  *Lead scoring*

- [ProspectLens Company Research](workflows/wwvUsosYUyMfpGbB_ProspectLens_company_research.json)  
  *Customer research*

- [HR-Focused Automation Pipeline with AI](workflows/t1P14FvfibKYCh3E_HR-focused_automation_pipeline_with_AI.json)  
  *HR automation*

- [CV Evaluation – Error Handling](workflows/vnhhf9aNsw0kzdBV_CV_Evaluation_-_Error_Handling.json)  
  *Resume evaluation system*

- [Spot Workplace Discrimination Patterns with AI](workflows/vzU9QRZsHcyRsord_Spot_Workplace_Discrimination_Patterns_with_AI.json)  
  *Workplace analytics tool*

### 🔧 Development and Maintenance Tools

- [Clone Workflows between n8n Instances using n8n API](workflows/yOhH9SGiZgZTDUB4_Clone_n8n_Workflows_between_Instances_using_n8n_API.json)  
  *Workflow migration*

- [Credentials Transfer](workflows/tlnJNm9t5H3VLU5K_Credentials_Transfer.json)  
  *Credentials management*

- [[OPS] Restore Workflows from GitHub to n8n](workflows/uoBZx3eMvLMxlHCS_[OPS]_Restore_workflows_from_GitHub_to_n8n.json)  
  *Workflow backup and restore*

- [Addon for Workflow Nodes Update Check Template](workflows/xlMrGt0c1eFi4J1U_Addon_for_Workflow_Nodes_Update_Check_Template.json)  
  *Update check tool*

- [Find Params with Affected Expressions Helper](workflows/zlHbtHIcCZ9enKwg_v1_helper_-_Find_params_with_affected_expressions.json)  
  *Debugging tool*

- [Test Webhooks in n8n without Changing WEBHOOK URL](workflows/sB6dC0GZ7zZHuMGF_Test_Webhooks_in_n8n_Without_Changing_WEBHOOK_URL_%28PostBin_%26_BambooHR_Example%29.json)  
  *Webhook testing*

- [Retry on Fail Except for Known Error Template](workflows/qAzZekQuABuH8uho_Retry_on_fail_except_for_known_error_Template.json)  
  *Error handling*

- [Web Server Monitor](workflows/pcLi17oUJK9pSaee_Web_Server_Monitor.json)  
  *System monitoring*

- [Suspicious Login Detection](workflows/xQHiKDTkezDY5lFu_Suspicious_login_detection.json)  
  *Security monitoring*

- [MAIA – Health Check](workflows/wng5xcxlYA6jFS6n_MAIA_-_Health_Check.json)  
  *System health monitoring*

- [Track Working Time and Pauses](workflows/pdgNdag49lwoTxUP_Track_Working_Time_and_Pauses.json)  
  *Time management*

- [Automated Work Attendance with Location Triggers](workflows/x2kgOnBLtqAjqUVS_Automated_Work_Attendance_with_Location_Triggers.json)  
  *Attendance system*

### 🔌 API & Integrations

- [OIDC Client Workflow](workflows/zeyTmqqmXaQIFWzV_OIDC_client_workflow.json)  
  *Authentication integration*

- [Use HttpRequest Node to Post on WordPress.com via XMLRPC](workflows/yPIST7l13huQEjY5_Use_XMLRPC_via_HttpRequest-node_to_post_on_Wordpress.com.json)  
  *WordPress integration*

- [Image Generation API](workflows/wDD4XugmHIvx3KMT_Image_Generation_API.json)  
  *Image generation service*

- [Generate 360° Virtual Try-on Videos for Clothing with Kling API](workflows/xQ0xqhNzFeEdBpFK_Generate_360°_Virtual_Try-on_Videos_for_Clothing_with_Kling_API.json)  
  *Virtual try-on*

- [Upload Video to Drive via Google Script](workflows/wGv0NPBA0QLp4rQ6_Upload_video_to_drive_via_google_script.json)  
  *File upload*

- [React to PDFMonkey Callback](workflows/s6nTFZfg6xjWyJRX_React_to_PDFMonkey_Callback.json)  
  *PDF processing callback*

- [Upload and Post Images](workflows/ra8MrqshnzXPy55O_upload-post_images.json)  
  *Image upload*

- [Luma AI – Webhook Response v1 – AK](workflows/rYuhIChQyjpGNvuR_Luma_AI_-_Webhook_Response_v1_-_AK.json)  
  *Webhook integration*
- [Luma AI – Webhook Response v1 – AK](workflows/rYuhIChQyjpGNvuR_Luma_AI_-_Webhook_Response_v1_-_AK.json)  
  *AI service integration*

### 📈 Analytics & Reporting

- [OpenSea Analytics Agent Tool](workflows/yRMCUm6oJEMknhbw_OpenSea_Analytics_Agent_Tool.json)  
  *NFT market analysis*

- [OpenSea AI-Powered Insights via Telegram](workflows/wi2ZWKN9XPR0jkvn_OpenSea_AI-Powered_Insights_via_Telegram.json)  
  *Intelligent analysis of the NFT market*

- [SERPBear Analysis Template](workflows/qmmXKcpJOCm9qaCk_SERPBear_analytics_template.json)  
  *SEO analysis*

- [Full Version of Google Maps](workflows/qhZvZVCoV3HLjRkq_Google_Maps_FULL.json)  
  *Map service integration*

- [Fetch Squarespace Blog and Event Collections to Google Sheets](workflows/sUGieRWulZJ7scll_Fetch_Squarespace_Blog_%26_Event_Collections_to_Google_Sheets__.json)  
  *Content analysis*

### 🎯 Professional Field Applications

- [Forward Netflix Emails to Multiple Addresses with Gmail and Mailjet](workflows/pkw1vY5q1p2nNfNC_Forward_Netflix_emails_to_multiple_email_addresses_with_GMail_and_Mailjet.json)  
  *Email forwarding*

- [Namesilo Bulk Domain Availability Check (Template)](workflows/phqg5Kk3YowxoMHQ_Namesilo_Bulk_Domain_Availability_[Template].json)  
  *Domain name check*

- [HDW Lead Geländewagen](workflows/piapgd2e6zmzFxAq_HDW_Lead_Geländewagen.json)  
  *Professional business process*

- [n8n-Agricultural Products](workflows/ziJG3tgG91Gkbina_n8n-Agricultural%20products.json)  
  *Agricultural applications*

- [General 3D Presentation](workflows/vpZ1wpsniCvKYjCF_General_3D_Presentation.json)  
  *3D content processing*

- [Translation](workflows/vssVsRO0FW6InbaY_Translate.json)  
  *Multi-language translation*

- [puq-docker-immich-deploy](workflows/qps97Q4NEet1Pkm4_puq-docker-immich-deploy.json)  
  *Container deployment*

- [InstaTest](workflows/qww129cm4TM9N8Ru_InstaTest.json)  
  *Test automation*

### 🔍 Document and Data Processing

- [Analyze Screenshots with AI](workflows/wDD4XugmHIvx3KMT_Analyze_Screenshots_with_AI.json)  
  *Image analysis*

- [Extract Text from PDF and Image Using Vertex AI (Gemini) into CSV](workflows/sUIPemKdKqmUQFt6_Extract_text_from_PDF_and_image_using_Vertex_AI_(Gemini)_into_CSV.json)  
  *Extract document content*

- [Create Unique Jira Tickets from Splunk Alerts](workflows/uD31xU0VYjogxWoY_Create_Unique_Jira_tickets_from_Splunk_alerts.json)  
  *Incident management*

### 🎮 Other Useful Tools

- [My Workflow](workflows/yYjRbTWULZuNLXM0_My_workflow.json)  
  *Personal workflow example*

- [My Workflow 6](workflows/rLoXUoKSZ4a9XUAv_My_workflow_6.json)  
  *Personal workflow example 6*

- [Workflow x2VUvhqV1YTJCIN0](workflows/x2VUvhqV1YTJCIN0_workflow_x2VUvhqV1YTJCIN0.json)  
  *Custom workflow example*
