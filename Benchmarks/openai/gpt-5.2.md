# GPT-5.2
**Анонс:** https://openai.com/uk-UA/index/introducing-gpt-5-2/ 

**Порівняння GPT-5.2.**
**Моделі запускалися з максимально доступним рівнем інтенсивності міркування в API OpenAI (xhigh для GPT‑5.2 Thinking і Pro та high для GPT‑5.1 Thinking), за винятком професійних оцінювань, де GPT‑5.2 Thinking запускалася з рівнем heavy — максимальним, доступним у ChatGPT Pro.**

| Бенчмарк | GPT-5.2 Thinking | GPT-5.2 Pro | GPT-5.1-Thinking |
| :-------- | :----------------: | :-----------: | :----------------: |
| GDPval (нічиї дозволені, перемоги або нічиї) | 70.9% | 74.1% | 38.8% (GPT-5) |
| GDPval (нічиї дозволені, лише впевнені перемоги) | 49.8% | 60.0% | 35.5% (GPT-5) |
| GDPval (без нічиїх) | 61.0% | 67.6% | 37.1% (GPT-5) |
| Investment banking spreadsheet tasks (внутрішні) | 68.4% | 71.7% | 59.1% |
| SWE-Bench Pro, Public | 55.6% | -- | 50.8% | 
| SWE-bench Verified | 80.0% | -- | 76.3% | 
| SWE-Lancer, IC Diamond* | 74.6% | -- | 69.7% | 
| ChatGPT відповіді без помилок (з пошуком) | 93.9% | -- | 91.2% | 
| ChatGPT відповіді без помилок (без пошуку) | 88.0% | -- | 87.3% | 
| OpenAI MRCRv2, 8 needles, 4k–8k | 98.2% | -- | 65.3% | 
| OpenAI MRCRv2, 8 needles, 8k–16k | 89.3% | -- | 47.8% | 
| OpenAI MRCRv2, 8 needles, 16k–32k | 95.3% | -- | 44.0% | 
| OpenAI MRCRv2, 8 needles, 32k–64k | 92.0% | -- | 37.8% | 
| OpenAI MRCRv2, 8 needles, 64k–128k | 85.6% | -- | 36.0% | 
| OpenAI MRCRv2, 8 needles, 128k–256k | 77.0% | -- | 29.6% | 
| BrowseComp Long Context 128k | 92.0% | -- | 90.0% | 
| BrowseComp Long Context 256k | 89.8% | -- | 89.5% | 
| GraphWalks bfs <128k | 94.0% | -- | 76.8% | 
| Graphwalks parents <128k | 89.0% | -- | 71.5% | 
| CharXiv reasoning (без інструментів) | 82.1% | -- | 67.0% | 
| CharXiv reasoning (з Python) | 88.7% | -- | 80.3% | 
| MMMU Pro (без інструментів) | 79.5% | -- | -- | 
| MMMU Pro (з Python) | 80.4% | -- | 79.0% | 
| Video MMMU (без інструментів) | 85.9% | -- | 82.9% | 
| Screenspot Pro (з Python) | 86.3% | -- | 64.2% | 
| Tau2-bench Telecom | 98.7% | -- | 95.6% | 
| Tau2-bench Retail | 82.0% | -- | 77.9% | 
| BrowseComp | 65.8% | 77.9% | 50.8% | 
| Scale MCP-Atlas | 60.6% | -- | 44.5% | 
| Toolathlon | 46.3% | -- | 36.1% | 
| GPQA Diamond (без інструментів) | 92.4% | 93.2% | 88.1% | 
| HLE (без інструментів) | 34.5% | 36.6% | 25.7% | 
| HLE (з пошуком, Python) | 45.5% | 50.0% | 42.7% | 
| MMMLU | 89.6% | -- | 89.5% | 
| HMMT, лютий 2025 (без інструментів) | 99.4% | 100.0% | 96.3% | 
| AIME 2025 (без інструментів) | 100.0% | 100.0% | 94.0% | 
| FrontierMath Tier 1–3 (з Python) | 40.3% | -- | 31.0% | 
| FrontierMath Tier 4 (з Python) | 14.6% | -- | 12.5% | 
| ARC-AGI-1 (Verified) | 86.2% | 90.5% | 72.8% | 
| ARC-AGI-2 (Verified) | 52.9% | 54.2% (high) | 17.6% |

_*У SWE-Lancer було виключено 40 із 237 задач, які не могли бути виконані на інфраструктурі OpenAI._

**Оригінали бенчмарків з анонсу по категоріям** 

![Професійний](/Benchmarks/images/gpt-52/gpt-52_01.png)

![Програмування](/Benchmarks/images/gpt-52/gpt-52_02.png) 

![Фактичність](/Benchmarks/images/gpt-52/gpt-52_03.png) 

![Розширений контекст](/Benchmarks/images/gpt-52/gpt-52_04.png) 

![Візуал](/Benchmarks/images/gpt-52/gpt-52_05.png) 

![Використання інструментів](/Benchmarks/images/gpt-52/gpt-52_06.png) 

![Академічність](/Benchmarks/images/gpt-52/gpt-52_07.png) 

![Абстрактне мислення](/Benchmarks/images/gpt-52/gpt-52_08.png) 