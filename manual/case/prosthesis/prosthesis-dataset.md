# Prosthesis Data

## Change Histories
- 23.10.26
  - Pontic의 label이 "Pontic" 에서 "Pontic And Mockup" 으로 변경되었습니다.
  - Pontic 카에고리에 Mockup 아이템이 추가되었습니다.

## Summary

아래 내용 중 label, value 외의 값은 입력 폼을 만들기 위해 RAYTeams에서 사용한 방식이 포함되어 있습니다.
입력 폼을 만들기 위한 값의 경우 추가/변경이 발생할 수 있습니다.
## Categories

### Props of Categories.
``` JSON
[
  {
    "value": "InlaysOnlaysAndVeneers",
    "label": "Inlays, Onlays And Veneers",
    "useable": true
  },
  {
    "value": "CrownsAndCopings",
    "label": "Crowns And Copings",
    "useable": true
  },
  {
    "value": "Pontics",
    "label": "Pontics And Mockup",
    "useable": true
  },
  {
    "value": "Waxup",
    "label": "Wax-up",
    "useable": true
  },
  {
    "value": "Splint",
    "label": "Splint",
    "useable": true
  },
  {
    "value": "Denture",
    "label": "Denture",
    "useable": true
  },
  {
    "value": "Orthodontics",
    "label": "Orthodontics",
    "useable": true
  },
]
```

### Description

| Pros  | Description |   
| -- | -- |   
| value | 카테고리의 실제 값 <br>Type에 정의되며 UI상 Type의 분류를 위해 사용됨 |   
| label | 표시되는 라벨 <br>엔드유저에게 노출되는 정보 |   
| useable | 사용 여부 |   

## Type

### Props of Types.
``` JSON
[
  {
    "value": "AnatomicInlay",
    "label": "Anatomic Inlay",
    "implantable": false,
    "category": "InlaysOnlaysAndVenners",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "Veneer",
    "label": "Veneer",
    "implantable": false,
    "category": "InlaysOnlaysAndVenners",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "OffsetInlay",
    "label": "Offset Inlay",
    "implantable": false,
    "category": "InlaysOnlaysAndVenners",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "AnatomicCrown",
    "label": "Anatomic Crown",
    "implantable": true,
    "category": "CrownsAndCopings",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "Coping",
    "label": "Coping",
    "implantable": true,
    "category": "CrownsAndCopings",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "OverpressCrown",
    "label": "Over-press Crown",
    "implantable": true,
    "category": "CrownsAndCopings",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "ProvisionalCrown",
    "label": "Provisional Crown",
    "implantable": false,
    "category": "CrownsAndCopings",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "SplintedCrown",
    "label": "Splinted Crown",
    "implantable": false,
    "category": "CrownsAndCopings",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "AnatomicPontic",
    "label": "Anatomic Pontic",
    "implantable": false,
    "category": "Pontics",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "OverpressPontic",
    "label": "Over-press Pontic",
    "implantable": false,
    "category": "Pontics",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "ProvisionalPontic",
    "label": "Provisional Pontic",
    "implantable": false,
    "category": "Pontics",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "ReducedPontic",
    "label": "Reduced Pontic",
    "implantable": false,
    "category": "Pontics",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "Mockup",
    "label": "Mockup",
    "implantable": false,
    "category": "Pontics",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "AnatomicWaxup",
    "label": "Anatomic Wax-up",
    "implantable": true,
    "category": "Waxup",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "ReducedWaxup",
    "label": "Reduced Wax-up",
    "implantable": true,
    "category": "Waxup",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "WaxupPontic",
    "label": "Pontic Wax-up",
    "implantable": false,
    "category": "Waxup",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "BiteSplint",
    "label": "Bite Splint",
    "implantable": false,
    "category": "Splint",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "BiteSplintGap",
    "label": "Bite SplintGap",
    "implantable": false,
    "category": "Splint",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "FullDenture",
    "label": "Full Denture",
    "implantable": false,
    "category": "Denture",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "PartialDenture",
    "label": "Partial Denture",
    "implantable": false,
    "category": "Denture",
    "hasMaterial": true,
    "useable": true
  },
  {
    "value": "Missing",
    "label": "Missing",
    "implantable": false,
    "materials": [
      "None"
    ],
    "category": "Orthodontics",
    "hasMaterial": false,
    "useable": true
  },
  {
    "value": "Anchor",
    "label": "Anchor",
    "implantable": false,
    "materials": [
      "None"
    ],
    "category": "Orthodontics",
    "hasMaterial": false,
    "useable": true
  },
  {
    "value": "Extraction",
    "label": "Extraction",
    "implantable": false,
    "materials": [
      "None"
    ],
    "category": "Orthodontics",
    "hasMaterial": false,
    "useable": true
  },
]
```

### Description

| Pros  | Description |   
| -- | -- |   
| value | Type에 대한 고유한 값 <br>이 값으로 report가 작성되어야함 |   
| label | 표시되는 Type에 대한 값 <br>엔드유저에게 노출되는 정보|   
| category | 타입이 UI상 표시될때 분류되는 기준 <br>report와는 무관하며 UI상에서만 사용됨 |   
| implantable | 임플란트 정보가 추가 가능한지 여부 |   
| hasMaterial | 소재 선택이 가능한지 여부 |   
| materials | 특정 소재만 선택이 가능한 경우 해당 소제의 value Array <br>이 값이 없다면 가능한 소재를 제공함(단 소재 속성 중 usedByType 이 true인 소재는 제외함) |   
| useable | 사용 여부 이 값이 false라면 UI에 표시하지 않음 |   


## Implant
> 임플란트는 Type에서 implantable이 true인 경우에만 유효한 값으로 계산됩니다.
> 임플란트가 선택되면 implant type도 반드시 설정 되어야 합니다.

### Props of Implant Value

```JSON
[
  { 
    "value": "CustomAbutment",
    "label": "Custom Abutment",
  },
  {
    "value": "StockAbutment",
    "label": "Stock Abutment",
  }
]
```

| Props | Description |
| -- | -- |
| value | Implant에 대한 고유한 값 <br>이 값으로 report가 작성 되어야함 |
| label | UI에 표시되는 Implant에 대한 값 |

### Props of Implant Type

```JSON
[
  {
    "value": "ScrewType",
    "label": "Screw Type"
  },
  {
    "value": "CementType",
    "label": "Cement Type"
  }
]
```

| Props | Description |
| -- | -- |
| value | Implant Type에 대한 고유한 값 <br>이 값으로 report가 작성 되어야함 |
| label | UI에 표시되는 Implant Type에 대한 값 |

## Materials

### Props of Materials
```JSON
[
  {
    "value": "PMMA",
    "label": "PMMA",
    "desc": "Polymethyl methacrylate",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "PEEK",
    "label": "PEEK",
    "desc": "PolyEtherEtherKetone",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "GCER",
    "label": "Glass ceramic",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "LS2",
    "label": "Lithium Disilicate Glass Ceramic",
    "desc": "e.g. Ivoclar e.max, HASS Amber",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "RC",
    "label": "Hybrid Ceramic",
    "desc": "Ultimate / enamic / cerasmart",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "ZI",
    "label": "Zirconia",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "MLZI",
    "label": "Multilayer zirconia",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "TZI",
    "label": "Translucent zirconia",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "AU",
    "label": "Gold",
    "shades": [],
    "useable": true
  },
  {
    "value": "NP",
    "label": "NP Metal",
    "desc": "Non Precious, not Titanium",
    "shades": [
      "MS"
    ],
    "useable": true
  },
  {
    "value": "TI",
    "label": "Titanium",
    "shades": [
      "MS"
    ],
    "useable": true
  },
  {
    "value": "WAX",
    "label": "Wax",
    "shades": [
      "VCL",
      "V3DM",
      "IVO"
    ],
    "useable": true
  },
  {
    "value": "None",
    "label": "None",
    "desc": "No material to be used",
    "shades": [],
    "useable": true
  }
]
```

### Description

| Pros  | Description |   
| -- | -- |   
| value | Material에 대한 고유 값 <br>이 값으로 report가 작성되어야함 |   
| label | 표시되는 Material 대한 값 <br>엔드유저에게 노출되는 정보 |   
| desc | 값에 대한 추가 정보 및 설명 |   
| shades | 지원하는 쉐이드 value Array <br>빈 배열인 경우 쉐이드를 지원하지 않음 |   
| usedByType | 소재가 type에 의해서만 제공되는지 여부 <br> 이 값이 true인 경우 기본 소재에서는 제외됨 |   
| useable | 사용 여부 |   

## Shades

### Props of Shades
```JSON
[
  {
    "value": "MS",
    "label": "Material Shade",
    "items": [
      "None",
      "Natural",
      "White",
      "Pink",
      "Yellow"
    ],
    "useable": true
  },
  {
    "value": "VCL",
    "label": "Vita Classic",
    "items": [
      "None",
      "A1",
      "A2",
      "A3",
      "A3.5",
      "A4",
      "B1",
      "B2",
      "B3",
      "B4",
      "C1",
      "C2",
      "C3",
      "C4",
      "D2",
      "D3",
      "D4"
    ],
    "useable": true
  },
  {
    "value": "V3DM",
    "label": "Vita 3D Master",
    "items": [
      "None",
      "0M1",
      "0M2",
      "0M3"
      "1M1",
      "1M2",
      "2L1",
      "2L2",
      "2M1",
      "2M2",
      "2M3",
      "2R1",
      "2R2",
      "3L1",
      "3L2",
      "3M1",
      "3M2",
      "3M3",
      "3R1",
      "3R2",
      "4L1",
      "4L2",
      "4M1",
      "4M2",
      "4M3",
      "4R1",
      "4R2",
      "5M1",
      "5M2",
      "5M3"
    ],
    "useable": true
  },
  {
    "value": "IVO",
    "label": "Ivoclar",
    "items": [
      "None",
      "01",
      "1A",
      "2A",
      "1C",
      "2B",
      "1D",
      "1E",
      "2C",
      "3A",
      "5B",
      "2E",
      "3E",
      "4A",
      "6B",
      "4B",
      "6C",
      "6D",
      "4C",
      "3C",
      "4D",
      "BL1",
      "BL2",
      "BL3",
      "BL4"
    ],
    "useable": true
  }
]
```

### Description

| Pros  | Description |
| -- | -- |
| value | Shade에 대한 고유 값 <br>이 값으로 report가 작성되어야함 |
| label | 표시되는 Shade 대한 값 <br>엔드유저에게 노출되는 정보 |
| items | 이 쉐이드가 제공하는 색상 값 배열 |
| useable | 사용 여부 |