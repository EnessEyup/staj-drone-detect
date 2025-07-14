# Day 2 Log
___
### Ne öğrendim ?
- Roboflow’dan YOLOv8 formatlı VisDrone veri seti indirme  
- Klasör yapısını Ultralytics standardına taşıma (`images/`, `labels/`)
- `data.yaml` yollarını düzenleme
- Jupyter defteriyle hızlı EDA (rastgele görseller + sınıf dağılımı)

### Karşılaşılan hatalar ?
- Çift “images/labels” alt-klasörü → glob 0 görüntü sorunu  
  - **Çözüm:** dosyaları bir üst dizine taşı / `rglob` kullan  
- Conda kernel’in Jupyter’de görünmemesi  
  - **Çözüm:** `ipykernel install --user --name cv`


