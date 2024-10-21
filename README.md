# VastAI Cloud Automation

This custom automation is designed to simplify the process of creating a machine on VastAI using the VastSDK for a non-technical client. The client wants to run the **TTS (Text-to-Speech) xtts-v2 model** on the cloud but has no experience with cloud infrastructure or programming. The goal is to provide a seamless automation solution (via script, executable, or batch file) that automatically searches for and selects the most cost-effective machine offers. Additionally, it should remotely launch Jupyter on the local system, eliminating the need to interact directly with the VastAI website.

### Client Requirements:
- Connect to VastAI Cloud through a shell or executable file.
- Retrieve offers for a specific template **[TTS-xtts-v2]** with filtering criteria, including:
  - CUDA version
  - GPU maximum RAM
  - GPU model
  - Machine price
  - DLP & other relevant parameters
- Automatically create an instance based on the defined filters.
- Upload files to the remote machine and execute startup commands.
- Run Jupyter Notebook locally but access it remotely via HTTPS.

### Automation Workflow:
- Read data from an Excel sheet.
- Transcribe each column and save the transcribed file to MEGA Cloud.
- Update the Excel sheet with a link to the transcribed file hosted on MEGA.
- Sample Excel sheet: [Sample Sheet](https://docs.google.com/spreadsheets/d/1BGuyZ-mkJ0L2O_nztQko8OrYjs0MJBu98t2-57HdKjc/edit?gid=0#gid=0)

### Presentation Slides:
- [presentation.pptx](https://github.com/user-attachments/files/17460375/presentation.pptx)

  

### Demo:

- ![17](https://github.com/user-attachments/assets/84540612-f279-4544-99fe-2eed7bd5397c)
- ![19](https://github.com/user-attachments/assets/e6c1514b-5de1-4f10-8d3d-e3f87e0489da)
- ![27](https://github.com/user-attachments/assets/7299920a-339e-4e0b-a242-6a5288930685)









 

