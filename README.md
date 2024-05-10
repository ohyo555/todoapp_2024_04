## 📑 할 일 리스트 구현

#### react를 이용한 할 일 목록 만들기

![todoapp](https://github.com/ohyo555/todoapp_2024_04/assets/153146836/9203cb6e-2709-422e-a9b1-649e4a8ca122)

- 구조
  * todosAtom: 할 일 목록을 관리
  * lastTodoIdAtom: 마지막 할 일의 ID를 관리
  * 커스텀 hook
    + useTodosStatus(): 할 일 관련 상태를 관리하고 할 일 추가, 삭제, 수정 등의 기능 제공
    + useTodoOptionDrawerStatus(): 할 일 옵션 관련 드로어를 열고 닫는 상태 관리
    + useEditTodoModalStatus(): 할 일 수정을 위한 모달을 열고 닫는 상태 관리
    + useNoticeSnackbarStatus(): 일시적인 메시지를 표시하기 위한 스낵바를 열고 닫는 상태 관리
  * 컴포넌트
    + NewTodoForm: 새로운 할 일을 추가하는 폼 렌더링
    + TodoListItem: 개별 할 일 항목을 표시하고 편집 및 삭제 제공
    + EditTodoModal: 특정 할 일 항목을 수정하기 위한 모달을 렌더링
    + TodoOptionDrawer: 특정 할 일 항목과 관련된 옵션(수정, 삭제)을 표시하는 Drawer를 렌더링
    + TodoList: 할 일 목록을 표시하고 TodoListItem을 사용하여 상태와 상호 작용을 관리
    + NoticeSnackbar: 일시적인 메시지를 표시하기 위한 스낵바를 렌더링
  * 스타일
    + Tailwind CSS 클래스 (tw-*)를 사용하여 컴포넌트 스타일링

![android](https://github.com/ohyo555/todoapp_2024_04/assets/153146836/d7162921-efc0-4156-b8cf-21b0f34c4f57)

- 위의 프로젝트를 android studio에서 실행
