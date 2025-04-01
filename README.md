# helm
## 0. structure
```
.
├── README.md
├── helmCharts
│   ├── README.md
|   ├── dev
│   ├── env
└── values
    ├── dev
    ├── env
```
## 1. Download
```
git clone url
```
## 2. Install
```
helm install name -n namespace helmCharts/env/<nameChart> --version <version> -f ../../values/env/<values.yaml>
```
> test