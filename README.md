# Knowledge-enhanced-Attack-Graph

## Instructions

Setup:

python 3.8
```
pip install -r requirements.txt
```

Running :
```
# Generating attack graph for CTI report
python main.py -M attackGraphGeneration -R "./Dataset/Evaluation/Frankenstein Campaign.txt" -O ./output.pdf
# Identifing techniques in CTI report
python main.py -M techniqueIdentification -T ./templates -R "./Dataset/Evaluation/Frankenstein Campaign.txt" -O ./output.pdf
```

Running - Archive-v0.1 (Archive-v0.1 is the experimental version without clear code structure and comments):
```
# Generating attack graph for CTI report
python attackGraph.py
# Identifing techniques in CTI report
python techniqueIdentifier.py
```

 - Sample Input and output can be found **[here](https://github.com/li-zhenyuan/Knowledge-enhanced-Attack-Graph/tree/main/Results)**.
 - Data Model required can bed found **[here](https://drive.google.com/drive/folders/1zVGPpN-i-BLlpFqQERscFGb45PkhfkUm?usp=sharing)**.

---
