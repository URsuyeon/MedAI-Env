
# MedAI-Env 설치 가이드

이 저장소는 의료 이미지 및 영상 딥러닝 환경인 `MedAI` 환경을 설치할 수 있는 `Conda` 환경 설정 파일을 제공합니다. 이 가이드는 환경을 설치하고 사용하는 방법을 안내합니다.

## 1. Git 저장소 클론

먼저 GitHub 저장소를 클론합니다.

```bash
git clone git@github.com:URsuyeon/MedAI-Env.git
cd MedAI-Env
```

## 2. Conda 환경 생성

환경을 생성하려면 `environment.yml` 파일을 사용하여 Conda 환경을 설정합니다.

```bash
conda env create -f environment.yml
```

위 명령어를 실행하면 `environment.yml`에 정의된 대로 필요한 패키지들이 설치되고, `MedAI` 환경이 자동으로 생성됩니다. 환경 이름은 `MedAI`로 기본 설정되어 있습니다.

## 3. 환경 활성화

환경이 생성되면 아래 명령어로 `MedAI` 환경을 활성화합니다.

```bash
conda activate MedAI
```

## 4. 환경 사용

이제 `MedAI` 환경을 활성화한 상태에서 필요한 패키지를 사용하거나, 프로젝트를 진행할 수 있습니다.

