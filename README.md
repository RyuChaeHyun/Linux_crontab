# <p align="center">[우리FISA 3기 클라우드 엔지니어링] crontab을 활용한 컴퓨터 자동 전원 관리 시스템 (PC-off) 🕥

---


## 개발팀원👨‍👨‍👧💻

| <img src="https://avatars.githubusercontent.com/u/65991884?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/90691610?v=4" width="80"> | <img src="https://avatars.githubusercontent.com/u/79312705?v=4" width="80"> |
|:---:|:---:|:---:|
| [류채현](https://github.com/RyuChaeHyun) | [이석철](https://github.com/SeokCheol-Lee) | [김상민](https://github.com/isshomin) |


---
<br>

## 개요 

- #### 이 프로젝트는 crontab을 이용하여 컴퓨터의 전원을 업무 시간에만 자동으로 켜고, 그 외의 시간에는 자동으로 종료하여 접속이 불가능하도록 설정하는 것을 목표로 한다. 이를 통해 에너지 효율성을 높이고 보안을 강화하며, 시스템의 수명을 연장할 수 있다.
- #### 정해진 근로시간에 PC를 종료시켜 정시 퇴근을 유도하고, 효율적인 근로시간 관리를 통해 직원들의 워라밸(Work and Life Balance)을 지켜주는 주 52시간 근무제 관리에 도움이 된다.

---
<br>

## 프로젝트 배경

- ### 많은 기업과 기관에서 컴퓨터가 24시간 내내 켜져 있어 불필요한 에너지 소비와 보안 위험에 노출되는 경우가 많다. 이러한 문제를 해결하고자 다음과 같은 필요성이 제기되었다.
  - #### 에너지 절약: 업무 시간 외에 컴퓨터를 종료함으로써 전력 소비를 감소시키고, 이에 따른 비용 절감 효과를 얻을 수 있다.
  - #### 보안 강화: 비업무 시간에 시스템 접근을 차단하여 외부 공격이나 내부 정보 유출의 위험을 최소화한다.
  - #### 시스템 유지보수 효율화: 하드웨어의 불필요한 가동을 줄여 장비의 수명을 연장하고 유지보수 비용을 절감한다.
 
---
<br>

## 주요기능

- ### 자동 해제: 지정된 업무 시작 시간에 계정잠금이 자동으로 해제된다.
- ### 자동 종료: 업무 종료 시간에 컴퓨터가 자동으로 꺼진다.
- ### 접근 제한: 업무 시간 외에는 원격 및 물리적 접근이 제한되어 보안성을 높인다.
