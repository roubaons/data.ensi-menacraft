Overview :

Menacraft is an AI-powered platform that helps detect misinformation by analyzing digital content.
It focuses on verifying both the authenticity of content and its contextual consistency.

Features :
(*)Content Authenticity
Detects manipulated or AI-generated content
Supports images, videos, and text
Provides a confidence score
Identifies suspicious patterns

(*)Contextual Consistency
Checks if content matches its caption or claim
Detects misleading or reused content
Provides a consistency score
Generates simple explanations
How It Works:

Upload content (image, video, or text)
AI analyzes:
Authenticity
Context consistency
Get results:
Status (Verified / Suspicious)
Scores
Explanation:

Tech Stack
Backend: FastAPI (Python)
AI: Machine Learning / Deep Learning
Computer Vision: OpenCV
NLP: Text analysis models
Frontend: HTML, CSS, JavaScript
Installation:
git clone https://github.com/your-username/menacraft.git
cd menacraft
pip install -r requirements.txt
uvicorn main:app --reload
Usage:
Open the app in your browser
Upload your content
View instant verification results
Example Output:

Status: Suspicious  
Authenticity Score: 80%  
Context Score: 45%  

Explanation:
- Possible manipulation detected  
- Caption does not match content  
Goal :

To restore trust in digital information through fast, transparent, and AI-driven verification.

License:

MIT License


