# 토이 프로젝트 가명 (Platzhalter)

## Introduction

### 목적

영어랑 달리 접근성이 낮은 독일어를 좀 더 체계적으로 공부하기 위한 목적으로 기획되었다. 사용자에게 단어 기반 서비스를 제공함으로써 단순히 단어장 역할뿐만 아니라, 더 나아가 통계적인 데이터 제공, 사용자 맞춤형 기반 서비스를 도입해 양질의 컨텐츠를 제공할 것이다.

나아가 사용자 맞춤형 서비스 고도화하기 위해 기계학습, 딥러닝 등이 추가될 수 있으며 챗봇, 문장 시스템 등 확장성을 바라보고 있다. 접근성이 낮은 언어를 **모두** 아우르는 서비스를 최종적인 목표로 바라본다.

### 간단한 동작 시나리오

사용자가 단어를 업로드(excel, csv or 직접 입력)하면, 해당 단어를 기반으로 다양한 단어 퀴즈를 생성한다. 사용자가 자주 틀리는 단어를 기반으로 분석 및 자료를 제공하고 이에 기반하여 **사용자 맞춤형 시험**을 제공한다.

## 기능

### 1. 단어 업로드

사용자는 csv, excel 등 파일을 업로드 하거나 직접 입력하여 단어장에 단어를 추가할 수 있다. 

### 2. 사용자 맞춤형 시험 제공

사용자가 특정 단어 집합(segment)을 선택 자주 틀리는 단어 혹은 경향을 파악하여 맞춤 시험을 제공한다.

### 3. 자주 틀리는 단어 등 통계적인 자료 제공

위에 설명한 시험을 기반으로 사용자에게 통계적인 자료를 시각화하여 제공한다.

### 4. 채팅 시스템 혹은 챗봇 제공(Optional)

### 5. 문장 시스템 도입(추후 제공)

### 6. 다른 언어로의 확장(최종 목표)

## 사용 기술 (예정)

- express
- elastic search
- postgreSQL
- typscript
- frontend framework(미정)
