# BullStreetBets

**ETF Recommender & Trend Spike Analyzer**

Python-based application to help identify sudden surges in public interest across any topic—from clean energy and artificial intelligence to consumer trends—and instantly recommend relevant ETFs aligned with those trends.

---

## Key Capabilities

### Dynamic Keyword Expansion
Automatically enriches your input keywords by pulling related terms from Wikipedia, WordNet, and semantic embeddings, ensuring you capture the full scope of a topic.

### Real-Time Data Collection
Continuously scrapes discussion data from Hacker News to quantify how frequently your keywords appear in online conversations.

### Spike Detection Engine
Calculates rolling statistics (mean, standard deviation, variance) and flags months when mentions significantly exceed historical averages, signaling emerging interest.

### ETF Recommendation Module
Matches your expanded keywords against hundreds of ETFs, ranking them by semantic similarity to help you find the most relevant investment vehicles.

### Automated Reporting & Visualization
Generates professional reports including trend plots, statistical summaries, and a clear list of recommended ETFs.

---

**Install dependencies:**
pip install -r requirements.txt

**Download NLTK data (one-time):**
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')

**Run Program:**
python app.py
   
