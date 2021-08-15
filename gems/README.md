# Repository of MIOM models

This repository contains metabolic networks converted to the `.miom` format. Files in this repository can be easily loaded using miom as follows:

```python
import miom
# @ indicates to search the file in this repositoy
network = miom.mio.load_gem('@homo_sapiens_human1.miom')
bigg_network = miom.mio.load_gem('@bigg/Recon3D.miom')
```

## List of models

