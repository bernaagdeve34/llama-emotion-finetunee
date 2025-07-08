LLaMA IMDb Sentiment Analysis (QLoRA)
Bu proje, TinyLlama adlı küçük ölçekli bir dil modelini IMDb film yorumları veri seti üzerinde QLoRA (Quantized Low-Rank Adaptation) yöntemi ile ince ayar yaparak duygu analizi gerçekleştirmeyi amaçlamaktadır.

İçerik
Transformer tabanlı TinyLlama modeline parameter-efficient fine-tuning (PEFT) uygulanması

IMDb veri setinin işlenmesi ve modellenmesi

QLoRA yöntemi ile düşük kaynak tüketimiyle model eğitimi

Model performansının değerlendirilmesi

Dosyalar
Dosya Adı	Açıklama
llama_imdbsonn.ipynb	Modelin eğitildiği Jupyter defteri
README.md	Proje açıklaması ve kullanım bilgileri

Kurulum ve Kullanım
Gerekli paketleri yükleyin:

nginx
Kopyala
Düzenle
pip install -r requirements.txt
Jupyter Notebook'u çalıştırarak tüm adımları takip edin:

nginx
Kopyala
Düzenle
jupyter notebook llama_imdbsonn.ipynb
Tüm işlemler notebook içinde adım adım açıklanmıştır.

Kullanılan Teknolojiler
TinyLlama (transformer tabanlı küçük dil modeli)

QLoRA (Low-Rank Adaptation yöntemi)

IMDb veri seti (Hugging Face üzerinden)

Hugging Face Transformers, PEFT, Datasets kütüphaneleri

Python, Jupyter Notebook

Model Performansı
Notebook'un sonunda doğruluk (accuracy), kayıp (loss) ve diğer değerlendirme metrikleri raporlanmıştır.

Kaynaklar
TinyLlama: https://github.com/jasonwei20/tiny-llama

QLoRA Makalesi: https://arxiv.org/abs/2305.14314

IMDb Dataset (HuggingFace): https://huggingface.co/datasets/imdb

PEFT Library: https://github.com/huggingface/peft

Geliştirici
Berna Agdeve
