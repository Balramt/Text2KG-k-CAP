# Evaluation Metrics Table

The following table presents the evaluation metrics for three different language models: **Alpaca-LoRA-13B**, **LLAMA3**, and **Vicuna-13B**. These metrics provide insights into the performance of each model across various categories, such as University, Musical Work, Airport, Building, Athlete, Politician, Company, Celestial Body, Astronaut, Comics Character, Means of Transportation, Monument, Food, Written Work, Sports Team, City, Artist, Scientist, and Film. The evaluation metrics include average precision, average recall, average F1 score.

### Combined Performance Metrics for LLM Models
| LLM Name           | Evaluation Metrics | avg_precision | avg_recall | avg_f1 |
|--------------------|--------------------|---------------|------------|--------|
|**LLama**           | University         | 0.58          | 0.41       | 0.46   |
|                    | Musicalwork        | 0.33          | 0.27       | 0.29   |
|                    | Airport            | 0.50          | 0.38       | 0.42   |
|                    | Building           | 0.51          | 0.45       | 0.46   |
|                    | Athlete            | 0.57          | 0.51       | 0.53   |
|                    | Politician         | 0.56          | 0.53       | 0.53   |
|                    | Company            | 0.64          | 0.54       | 0.57   |
|                    | Celestialbody      | 0.62          | 0.61       | 0.61   |
|                    | Astronaut          | 0.54          | 0.50       | 0.51   |
|                    | Comicscharacter    | 0.49          | 0.47       | 0.48   |
|                    | Meanoftransportation | 0.42        | 0.33       | 0.35   |
|                    | Monument           | 0.20          | 0.19       | 0.19   |
|                    | Food               | 0.63          | 0.59       | 0.60   |
|                    | Writtenwork        | 0.60          | 0.58       | 0.58   |
|                    | Sportsteam         | 0.58          | 0.56       | 0.56   |
|                    | City               | 0.16          | 0.17       | 0.17   |
|                    | Artist             | 0.45          | 0.35       | 0.38   |
|                    | Scientist          | 0.74          | 0.65       | 0.68   |
|                    | Film               | 0.45          | 0.39       | 0.41   |
|--------------------|--------------------|---------------|------------|--------|
|                    | **Average**        | 0.50          | 0.44       | 0.46   |
|--------------------|--------------------|---------------|------------|--------|
| **Mistral**        | University         | 0.34          | 0.11       | 0.16   |
|                    | Musicalwork        | 0.16          | 0.11       | 0.12   |
|                    | Airport            | 0.25          | 0.10       | 0.14   |
|                    | Building           | 0.39          | 0.13       | 0.19   |
|                    | Athlete            | 0.40          | 0.14       | 0.21   |
|                    | Politician         | 0.46          | 0.16       | 0.23   |
|                    | Company            | 0.48          | 0.20       | 0.27   |
|                    | Celestialbody      | 0.57          | 0.25       | 0.33   |
|                    | Astronaut          | 0.46          | 0.13       | 0.20   |
|                    | Comicscharacter    | 0.42          | 0.14       | 0.21   |
|                    | Meanoftransportation | 0.29        | 0.10       | 0.14   |
|                    | Monument           | 0.16          | 0.05       | 0.08   |
|                    | Food               | 0.47          | 0.16       | 0.24   |
|                    | Writtenwork        | 0.39          | 0.13       | 0.20   |
|                    | Sportsteam         | 0.25          | 0.08       | 0.12   |
|                    | City               | 0.03          | 0.01       | 0.01   |
|                    | Artist             | 0.33          | 0.11       | 0.17   |
|                    | Scientist          | 0.60          | 0.33       | 0.39   |
|                    | Film               | 0.40          | 0.22       | 0.26   |
|--------------------|--------------------|---------------|------------|--------|
|                    | **Average**        | 0.33          | 0.16       | 0.20   |
|--------------------|--------------------|---------------|------------|--------|
|**Alpaca-LoRA-13B** | University         | 0.29          | 0.16       | 0.20   |
|                    | Musicalwork        | 0.18          | 0.15       | 0.15   |
|                    | Airport            | 0.28          | 0.18       | 0.20   |
|                    | Building           | 0.35          | 0.27       | 0.29   |
|                    | Athlete            | 0.38          | 0.30       | 0.32   |
|                    | Politician         | 0.39          | 0.27       | 0.30   |
|                    | Company            | 0.35          | 0.21       | 0.25   |
|                    | Celestialbody      | 0.52          | 0.44       | 0.47   |
|                    | Astronaut          | 0.34          | 0.21       | 0.25   |
|                    | Comicscharacter    | 0.52          | 0.41       | 0.45   |
|                    | Meanoftransportation | 0.13        | 0.09       | 0.10   |
|                    | Monument           | 0.11          | 0.07       | 0.08   |
|                    | Food               | 0.38          | 0.30       | 0.31   |
|                    | Writtenwork        | 0.39          | 0.35       | 0.36   |
|                    | Sportsteam         | 0.41          | 0.28       | 0.31   |
|                    | City               | 0.10          | 0.09       | 0.09   |
|                    | Artist             | 0.35          | 0.22       | 0.26   |
|                    | Scientist          | 0.42          | 0.33       | 0.34   |
|                    | Film               | 0.18          | 0.14       | 0.15   |
|--------------------|--------------------|---------------|------------|--------|
|                    | **Average**        | 0.27          | 0.23       | 0.25   |
|--------------------|------------------------|---------------|------------|--------|
| **Vicuna           | University             | 0.31          | 0.19       | 0.23   |
|                    | Musicalwork            | 0.20          | 0.18       | 0.18   |
|                    | Airport                | 0.33          | 0.24       | 0.27   |
|                    | Building               | 0.48          | 0.33       | 0.38   |
|                    | Athlete                | 0.33          | 0.26       | 0.29   |
|                    | Politician             | 0.39          | 0.28       | 0.32   |
|                    | Company                | 0.49          | 0.37       | 0.41   |
|                    | Celestialbody          | 0.48          | 0.46       | 0.46   |
|                    | Astronaut              | 0.40          | 0.28       | 0.32   |
|                    | Comicscharacter        | 0.41          | 0.41       | 0.40   |
|                    | Meanoftransportation   | 0.22          | 0.17       | 0.18   |
|                    | Monument               | 0.04          | 0.05       | 0.05   |
|                    | Food                   | 0.43          | 0.39       | 0.39   |
|                    | Writtenwork            | 0.40          | 0.34       | 0.36   |
|                    | Sportsteam             | 0.52          | 0.38       | 0.42   |
|                    | City                   | 0.12          | 0.12       | 0.12   |
|                    | Artist                 | 0.30          | 0.21       | 0.23   |
|                    | Scientist              | 0.52          | 0.43       | 0.46   |
|                    | Film                   | 0.23          | 0.19       | 0.20   |
|--------------------|------------------------|---------------|------------|--------|
|                    | **Average**            | 0.36          | 0.26       | 0.29   |
|--------------------|------------------------|---------------|------------|--------|
