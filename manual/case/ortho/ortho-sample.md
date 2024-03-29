# Orthodontics Cases

## Summary

Orthodontics Case에 대한 예시를 정리합니다.

## Case A

### Description
 - 11번 치아는 anchor 임
 - 치아의 컨디션은 open_bite, other, spacing, crowding 이 4개의 상태를 가짐

### Case Data
```JSON
{
  "report_version": "RV1",
  "type": "orthodontics",
  "provider": "rayteams",
  "report": {
    "data": [
      {
        "key": 11,
        "type": "anchor",
        "ortho_status": "anchor"
      }
    ],
    "medicalReport": {
      "conditions": [
        "open_bite",
        "other",
        "spacing",
        "crowding"
      ]
    },
    "memo": "이것은 테스트 케이스 입니다."
  },
  "reversion": 1,
  "photos": {
    "front_face_aspect": ".teams_medias/FFA.jpg",
    "front_intra_oral": ".teams_medias/FIO.jpg",
    "front_smile": ".teams_medias/FSM.jpg",
    "left_intra_oral": ".teams_medias/LIO.jpg",
    "max_intra_oral": ".teams_medias/MAX.jpg",
    "maxillary_dentition_buccal": ".teams_medias/MDB.jpg",
    "right_face_aspect": ".teams_medias/RFA.jpg",
    "right_intra_oral": ".teams_medias/RIO.jpg",
    "right_smile": ".teams_medias/RSM.jpg"
  }
}
```

## Case B

### Description
- 16, 26 번 치아는 anchor
- 13번은 missing 
- 23번은 extraction
- 치아의 컨디션은 spacing, crowding 이 2개의 상태를 가짐
- Method of Gaining space 에서는 다음의 값들을 가짐
  - Selecting teeth to move(key: selectingTeethToMove): 5-5
  - Extraction(which tooth to extract)(key: extractionExtract): Primary
  - Extraction(key: extraction): Primary
  - Interproximal Reduction(key: interproximal): Secondary
  - Distalzation(key: distalization): None
  - Proclination(key: proclination): Refer to Clinical Simulation
- Midline: Correct upper by 1-5 mm
- Crossbite: Improve

### Case Data

```JSON
{
  "report_version": "RV1",
  "type": "orthodontics",
  "provider": "rayteams",
  "report": {
    "data": [
      {
        "key": 16,
        "type": "anchor",
        "ortho_status": "anchor"
      },
      {
        "key": 13,
        "type": "missing",
        "ortho_status": "missing"
      },
      {
        "key": 23,
        "type": "extraction",
        "ortho_status": "extraction"
      },
      {
        "key": 26,
        "type": "anchor",
        "ortho_status": "anchor"
      }
    ],
    "medicalReport": {
      "conditions": [
        "crowding",
        "spacing"
      ],
      "notMove": [
        "upper"
      ],
      "selectingTeethToMove": "5-5",
      "extractionExtract": "primary",
      "extraction": "primary",
      "interproximal": "secondary",
      "distalization": "none",
      "proclination": "simulation",
      "midline": [
        "correct_upper_by_1_5mm"
      ],
      "crossbite": "improve"
    },
    "memo": "This is orthodontics case B"
  },
  "reversion": 1,
  "photos": {
    "front_face_aspect": ".teams_medias/FFA.jpg",
    "front_intra_oral": ".teams_medias/FIO.jpg",
    "front_smile": ".teams_medias/FSM.jpg",
    "left_intra_oral": ".teams_medias/LIO.jpg",
    "max_intra_oral": ".teams_medias/MAX.jpg",
    "maxillary_dentition_buccal": ".teams_medias/MDB.jpg",
    "right_face_aspect": ".teams_medias/RFA.jpg",
    "right_intra_oral": ".teams_medias/RIO.jpg",
    "right_smile": ".teams_medias/RSM.jpg"
  }
}
```