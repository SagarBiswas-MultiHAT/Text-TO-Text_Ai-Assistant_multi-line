# Sagar - Your Virtual Assistant  

Sagar is a virtual assistant designed for aspiring cybersecurity professionals and CSE students. It processes user commands to open websites, play music, or provide AI-generated responses, offering a hands-on experience with automation and AI technologies.  

## Features  
- **Website Navigation**: Quickly open popular websites like Google, YouTube, GitHub, and more.  
- **Music Playback**: Play songs using predefined links from a custom music library.  
- **AI-Powered Responses**: Leverages Groq API for intelligent and context-aware replies.  
- **Flexible Input Modes**: Supports both single-line and multi-line command inputs.  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/SagarBiswas-MultiHAT/Text-TO-Text_Ai-Assistant_multi-line.git
   cd Text-TO-Text_Ai-Assistant_multi-line
   ```  

2. Install the required Python packages:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Ensure you have a valid Groq API key. Replace the placeholder in the code with your key.  

## Usage  

### Single-Line Input  
Run `main_single-line.py` to issue commands one at a time:  
```bash  
python main_single-line.py  
```  
Example input:  
```
==> open google  
```  

### Multi-Line Input  
Run `main_multiple-line.py` to input commands across multiple lines:  
```bash  
python main_multiple-line.py  
```  
Enter commands line by line and type `END` to process them:  
```
Enter your command (type 'END' on a new line to finish):  
play song_name  
END  
```  

## Command Examples  
- **Open Websites**:  
  - `open google`  
  - `open youtube`  

- **Play Songs**:  
  - `play song_name`  

- **Ask Questions**:  
  - `What is cybersecurity?`  
  - `How can I secure my network?`  

## Customization  
You can add more websites or music links in the `url_map` and `musicLibraries.musicLinks` dictionary, respectively.  

## Contributions  
Contributions are welcome! Feel free to open issues or submit pull requests.  

## License  
This project is licensed under the [MIT License](LICENSE).  

---  
Sagar is here to make your journey into cybersecurity smoother and more engaging. 🚀
