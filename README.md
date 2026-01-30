23640731 - Nguyễn Nam Trung Nguyên
Bài tập ReactJs tuần 3
Buổi 3 – React Hook
Bài tập 1: Form & Controlled Components
      Mục tiêu
          ●	Quản lý state phức tạp
      Bài tập
      Form thông tin người dùng
          ●	name
          ●	email
          ●	age
      Yêu cầu
          ●	State là object
          ●	Không mutate state trực tiếp
          ●	Update từng field bằng spread operator
Bài tập 02:  useEffect cơ bản (Lifecycle)
      Mục tiêu
          ●	Hiểu side effect
          ●	Lifecycle trong function component
      Đề bài
      Digital Clock
          ●	Hiển thị giờ hiện tại
          ●	Cập nhật mỗi 1 giây
      Yêu cầu
          ●	Dùng useEffect
          ●	Cleanup setInterval
Bài tập 03: “Product Filter + Tổng tiền”
          ●	Có danh sách 1.000–5.000 sản phẩm (mock array).
          ●	Cho phép search theo tên + filter theo khoảng giá.
          ●	Tính tổng tiền của danh sách đang lọc.
      Yêu cầu
          ●	Dùng useMemo cho:
              ○	danh sách sau filter/sort
              ○	tổng tiền
          ●	So sánh render: log thời gian trước/sau tối ưu.
Bài tập 04: “Todo List Performance”
          ●	TodoApp có TodoInput, TodoList, TodoItem.
          ●	Gõ vào input không được làm re-render toàn bộ list (khi list lớn).
          Yêu cầu
          ●	TodoItem bọc React.memo
          Hàm onDelete, onToggle dùng useCallback
          ●	Kiểm tra bằng console.log("render item", id).
Bài tập 05: “Stopwatch”
          ●	Start / Pause / Reset
          ●	Hiển thị milliseconds
          ●	Focus input “Lap name” khi bấm “Add Lap”
      Yêu cầu
          ●	useRef lưu intervalId
          ●	useRef để focus input
          ●	Không dùng state để lưu intervalId.

Bài tập 06: “Fetch Users State Machine”
          ●	idle → loading → success | error
          ●	Có nút Retry
      Yêu cầu
          ●	useReducer quản lý state theo action:
              ○	FETCH_START, FETCH_SUCCESS, FETCH_ERROR
          ●	Reducer phải pure function
          ●	UI hiển thị đúng trạng thái.
Bài tập 07: “Theme Switcher”
          ●	Light / Dark
          ●	Có 3 cấp component (App → Layout → Card → Button)
          Yêu cầu
          ●	Tạo ThemeContext
          ●	useContext lấy theme ở component sâu
          ●	Theme đổi là toàn UI đổi.
          Bonus
          ●	Persist theme bằng localStorage (kết hợp useEffect).
