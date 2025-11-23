# MachineLearningProject_GKLL
Machine Learning Lecture's Final Project of Gong, Kim, Lim, Lee
## Colab에서 GitHub로 파일 커밋하기

이 문서에서는 Google Colaboratory(Colab)에서 작업한 파일을 GitHub의 `machinelearningproject_GKLL` 리포지토리의 특정 브랜치에 커밋하는 방법을 설명합니다.

### 1. Colab에서 파일 생성 또는 작업

먼저 Colab에서 새 노트북 파일을 생성하거나 기존 노트북 파일을 열어 작업을 진행합니다. 여러분의 담당 파트에 해당하는 코드를 작성하거나 문서를 준비합니다.

### 2. GitHub에 사본 저장 및 커밋

작업이 완료되면 다음 단계를 통해 GitHub 리포지토리에 파일을 커밋할 수 있습니다.

1.  **파일 메뉴 접근**: Colab 노트북의 왼쪽 상단에 있는 `파일(File)` 메뉴를 클릭합니다.
2.  **GitHub에 사본 저장 선택**: 드롭다운 메뉴에서 `GitHub에 사본 저장(Save a copy to GitHub)` 옵션을 선택합니다.
3.  **리포지토리 및 브랜치 선택**: 새 창이 나타나면 다음과 같이 설정합니다.
    *   **Repository (리포지토리)**: `machinelearningproject_GKLL`을 선택합니다.
    *   **Branch (브랜치)**: 파일을 커밋할 원하는 브랜치(예: `main`, `dev`, 또는 개인 작업 브랜치)를 선택합니다.
    *   **File path (파일 경로)**: 저장할 파일의 경로와 이름을 지정합니다. (예: `src/my_task/my_notebook.ipynb`)
4.  **커밋 메시지 작성**: 적절한 커밋 메시지를 작성하여 어떤 변경사항인지 명확히 합니다.
5.  **OK 버튼 클릭**: 모든 설정을 확인한 후 `OK` 버튼을 클릭하면 Colab 파일이 지정된 GitHub 리포지토리 및 브랜치에 커밋됩니다.

이 과정을 통해 여러분의 Colab 작업 내용을 GitHub 리포지토리에 효과적으로 공유하고 관리할 수 있습니다.

## 3. 사용 예시

예를 들어 저는 사용자 K이고, Github 사이트에 들어가보니 `machinelearningproject_GKLL` 레포지토리 내에 파일이 다음과 같이 있다고 해봅시다. ([src]는 그냥 파일들이 들어있는 폴더 이름이고, 이는 [notebooks]도 마찬가지입니다. 중요한 건 .ipynb 또는 .py입니다.)

```
machinelearningproject_GKLL/
├── src/
│   ├── data_preprocessing/
│   │   └── preprocess_data.ipynb
│   ├── models/
│   │   └── train_model.ipynb
│   └── utils/
│       └── helper_functions.py
├── notebooks/
│   └── exploratory_analysis.ipynb
└── README.ipynb
```

만약 제가 `src/data_preprocessing` 파트를 담당하여 새로운 전처리 스크립트 `clean_data.ipynb`를 추가하고 싶다면, Colab에서 이 파일을 작업한 후 'GitHub에 사본 저장' 옵션에서 다음과 같이 설정하여 커밋할 수 있습니다.

*   **Repository (리포지토리)**: `machinelearningproject_GKLL`
*   **Branch (브랜치)**: `dev-k` (개인 작업 브랜치 또는 팀의 개발 브랜치)
*   **File path (파일 경로)**: `src/data_preprocessing/clean_data.ipynb`
*   **커밋 메시지**: `feat: Add new data cleaning script for preprocessing`

이렇게 설정하고 `OK` 버튼을 클릭하면, 제 작업물이 `machinelearningproject_GKLL` 리포지토리의 `dev-k` 브랜치에 `src/data_preprocessing/clean_data.ipynb` 경로로 추가됩니다.
### 4. 사용 예시 2

또 다른 사용 예시로, 이 파일의 유형은 markdown 파일이며 설명서 역할을 하는 파일 형식을 뜻합니다. 이름을 보면 README.ipynb 라고 되어있습니다.

이 파일은 동일하게 레포지토리 machinelearningproject_GKLL 에 README.ipynb로 들어가있는데, 이게 어떻게 가능한 걸까요?

지금 우리가 colab에서 편집하고 있는 이 파일은 아직 레포지토리 machinelearningproject_GKLL 에 넣기 전 버전, 즉 Github에 제출하기 전 다른 회사인 Google의 클라우드를 빌려서 코드를 만들고 있는 상태라는 것을 염두에 둘 필요가 있습니다. 

따라서 Github에 사본 복사하기를 누르고 제출하는 순간, Github의 machinelearningproject_GKLL 에 수정된 파일 README.ipynb가 생기는 것이죠. 

당신은 원격으로 파일을 편집하고, 사본 복사하기를 통해 비로소 동기화를 하는 셈입니다. 

지금 편집기는 google에서 제공하는 공간에서 하고 있는 것이고, 이는 본래 Github, Git과 아무 상관이 없는 별도의 회사의 별도의 공간에서 편집하고있다는 뜻입니다.
