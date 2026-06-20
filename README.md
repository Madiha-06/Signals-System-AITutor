# Signals & Systems AI Tutor
A domain-specific AI tutoring chatbot built for Computer Engineering students studying Signals and Systems. Powered by the Google Gemini API with a Python Tkinter desktop GUI.

## Features
- Conversational AI tutor strictly scoped to Signals & Systems course topics
- One-shot prompting for consistent, course-accurate responses
- Guardrail-enforced system prompt to prevent out-of-scope answers
- Clean plain-text formula output (no LaTeX or markdown)
- Multi-threaded API calls so the UI never freezes
- Scrollable chat interface with real-time responses

## Topics Covered
The tutor only answers questions within the following course syllabus:
- Continuous-time and Discrete-time signals
- Elementary signals (Step, Ramp, Impulse, Sinusoidal, Exponential etc.)
- System classifications (Linear/Non-linear, Time-variant/Invariant, Causal/Non-causal)
- Convolution Sum and Convolution Integral
- Fourier Series and Fourier Transform
- Laplace Transform and ROC
- Z-Transform and Inverse Z-Transform
- Sampling, Aliasing, DTFT, and Difference Equations
- Cross-correlation and Auto-correlation
- 
## Tech Stack
- **Python** — core language
- **Tkinter** — desktop GUI
- **Google Gemini API** — AI responses
- **Threading** — non-blocking UI during API calls

## Setup
1. Clone the repository
   git clone https://github.com/Madiha-06/signals-system-AITutor.git
   cd signals-system-AITutor
2. Install dependencies
   pip install google-generativeai
3. Add your Gemini API key
   python
   client = genai.Client(api_key="YOUR_API_KEY")
4. Run the app
   python main.py
   
## References
- Schaum's Outlines: Signals and Systems — Hwei Hsu
- Electronic Signals and Systems — Syed K. Hasnain
