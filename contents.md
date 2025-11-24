graph TD
    %% 1. 메인 주제 노드 정의 (Markdown 볼드체 사용하지 않음)
    MOD_TITLE[IaC 기반 클라우드 구축 (총 32시간)]
    
    %% 2. 서브그래프를 이용한 모듈 그룹화
    subgraph 강의 세부 모듈
        MOD1(1. IaC 및 DevOps 기본 개념);
        MOD2(2. Terraform 실습 및 상태 관리);
        MOD3(3. 클라우드 환경 배포 자동화);
    end
    
    %% 3. 노드 간의 순서 연결 (흐름)
    MOD_TITLE --> MOD1;
    MOD1 --> MOD2;
    MOD2 --> MOD3;
    
    %% 4. 시각적 강조를 위한 스타일링 (Gemini 3.0 스타일)
    style MOD_TITLE fill:#4CAF50, stroke:#388E3C, color:#FFFFFF
    style MOD1 fill:#B2EBF2, stroke:#00BCD4
    style MOD2 fill:#FFF9C4, stroke:#FFEB3B
    style MOD3 fill:#FFCCBC, stroke:#FF5722
