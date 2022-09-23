---
layout: post
title:  "Scheduling Algorithm Simulator"
info: "Scheduling Algorithm Simulator"
tech: "Golang"
type: OS 
---

## Scheduling Algorithm Simulator
해당 프로젝트는 학교에서 운영체제 (Operating System) 과목을 수강하며 학습한 스케줄링 기법을 기반으로
여러 스케줄링 알고리즘을 시각적으로 시뮬레이트 해주는 프로그램을 개발한 개인 프로젝트이다.

지원하는 스케줄링 알고리즘은 아래와 같다.
* FIFO (First-in-First-Out)
* RR (Round Robin)
* SJF (Shortest Job First)
* STCF (Shortest To Complete First)
* MLFQ (Multi-Level Feedback Queue)


운용자가 수행할 프로세스 (Job) 개수 및 각 Job의 Arrival_Time, Service_Time 을 입력하면
프로그램은 프로세스 수행 Flow를 Result.txt 파일에 작성하여 보여준다.


## Techique
해당 프로젝트는 Golang 언어로 작성했습니다.  


## Duration 
2022년 9월 ~ 2022년 10월 진행  
