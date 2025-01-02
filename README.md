# Java 연락처 관리 프로그램 (Hashmap 사용)

이 프로그램은 연락처를 생성, 읽기, 수정, 삭제할 수 있는 기능을 제공합니다.

생성된 연락처는 바이너리 파일로 로컬에 저장되어 지속적으로 관리됩니다.

## 프로그램 설명

- **연락처 생성**: 새로운 연락처를 추가합니다.
- **연락처 업데이트**: 기존 연락처 정보를 수정합니다.
- **연락처 삭제**: 지정된 연락처를 삭제합니다.
- **저장된 연락처 읽기**: 저장된 연락처 목록을 읽습니다.
- **로컬 파일 저장**: 연락처는 `hashmap_data.bin`라는 바이너리 파일에 저장됩니다.

### 연락처 생성
- 연락처 등록 시, 사용자로부터 이름, 전화번호, 주소, 관계를 입력받습니다.
- 전화번호는 반드시 `010`으로 시작하는 10자리 또는 11자리의 숫자여야 하며, 중복된 전화번호는 입력할 수 없습니다.
- 관계는 `가족`, `친구`, `기타` 중에서 선택해야 합니다.

### 연락처 업데이트
- 기존의 연락처 정보를 수정할 수 있습니다.
- 이름으로 검색하여 해당 연락처를 찾고, 수정 여부를 확인한 후 정보를 업데이트합니다.
- 만약 동일한 이름을 가진 사람이 여러 명 있을 경우, 수정할 사람을 번호로 선택할 수 있습니다.
- 전화번호는 수정 후 중복을 체크하며, 수정 후 변경된 내용을 저장합니다.

### 3. 연락처 삭제
- 이름을 기준으로 연락처를 삭제할 수 있습니다. 만약 동일한 이름을 가진 사람이 여러 명 있을 경우, 삭제할 사람을 번호로 선택할 수 있습니다.

### 4. 저장된 연락처 읽기
- 저장된 연락처 목록을 읽어올 수 있습니다.
- 프로그램이 종료된 후에도 `hashmap_data.bin` 파일에 저장된 연락처 데이터를 읽어와서 이어서 사용할 수 있습니다.

### 5. 로컬 파일 저장
- 연락처 정보는 `hashmap_data.bin`라는 바이너리 파일에 저장됩니다.
- 프로그램이 종료되면, 현재 상태가 자동으로 파일에 저장되고, 다음에 프로그램을 실행할 때 저장된 데이터를 읽어옵니다.

<hr/>

#### 프로그램 처음으로 시작 

![image](https://github.com/user-attachments/assets/ffabf6c1-5b86-4269-bf37-7d23bda6cfe1)


#### 연락처 추가

![image](https://github.com/user-attachments/assets/b221faa7-5133-4aa5-8f9f-7ae748782c7b)

![image](https://github.com/user-attachments/assets/c203bc22-9239-4fa0-b7a3-dab05f548800)

#### 저장된 연락처 읽기

![image](https://github.com/user-attachments/assets/e1f7bebd-78e2-4199-95a0-d281734a477d)

#### 연락처 업데이트

![image](https://github.com/user-attachments/assets/1d3ea6f7-7c05-41bf-80b0-b0d4e8378dde)

![image](https://github.com/user-attachments/assets/8f691942-27e4-4275-bfad-04c73001c491)

![image](https://github.com/user-attachments/assets/fe99e495-5172-41c1-bbcf-26bb589221fb)

#### 연락처 삭제

![image](https://github.com/user-attachments/assets/51b60282-10d6-436d-9cc3-3f55412bc99a)

![image](https://github.com/user-attachments/assets/279b6483-3459-43af-95b6-c6d21a3432d4)

#### 로컬 파일 저장

![image](https://github.com/user-attachments/assets/3d4083d6-9f1b-4150-b4ac-dcdea3c6ae93)

#### 저장된 연락처 읽기

![image](https://github.com/user-attachments/assets/931007bc-6b58-47f7-917d-91d3aaccda0d)
