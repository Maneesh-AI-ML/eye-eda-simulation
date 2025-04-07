# Eye Tracking & EDA Signal Integration (Simulated)

This project simulates a realistic experimental pipeline that combines **eye tracking** and **electrodermal activity (EDA)** signals in response to visual stimuli — inspired by human behavior studies in immersive environments like those in the CONTINUUM platform.

## 🧪 Project Goals

- Simulate gaze and EDA signals for 3 stimuli: Happy Child, Angry Dog, and Neutral Scene
- Align and synchronize data using timestamps
- Apply signal filtering (Butterworth low-pass) to clean EDA
- Detect and visualize SCR (Skin Conductance Responses)
- Combine gaze + EDA to interpret emotional & attention response together

## 📁 Folder Structure

```bash
├── notebook/
│   └── realistic_eda_eye_pipeline.ipynb
├── data/
│   ├── [eye_tracking_data].csv
│   ├── [eda_data].csv
│   └── [stimuli].csv
├── images/
│   └── [plots].png

## 🛠️ Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib  
- SciPy (signal processing)  
- Jupyter Notebook

## 📊 Outputs

- Filtered EDA signal with SCR peaks  
- Combined plot of gaze + EDA + stimulus timeline  
- Time-locked multimodal visualization

## 👤 Author

**Maneesh Mishra**  
PhD in Automatique et Productique  
Université de Lille  
🌐 [LinkedIn](https://www.linkedin.com/in//maneesh-ai-ml/)
)  
📫 Contact: maneesh09mishra@gmail.com

## 📄 License

This project is licensed under the MIT License.
