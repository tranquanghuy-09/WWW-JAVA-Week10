# Practice week 10 of WWW programming (Java) 
Security
    <table style="border-collapse: collapse;">
        <tr>
            <td style="border: 1px solid black;padding: 10px;">FullName: </td>
            <td style="border: 1px solid black;padding: 10px;font-weight: bold; color: red;">Trần Quang Huy</td>
        </tr>
        <tr>
            <td style="border: 1px solid black; padding: 10px;">StudentID: </td>
            <td style="border: 1px solid black;padding: 10px; font-weight: bold; color: red;">20092731</td>
        </tr>
    </table>

# DESCRIPTION:
## Spring Security
- Authentication: Bằng User name và User password lưu vào memory (inMemoryAuthentication) hoặc xuống database (jdbcAuthentication)
- Authorization: Khi đã xác thực thành công người dùng, dựa vào role, người dùng có thể sử dụng các dịch vụ được cấp từ trước
  
## Store Database
- Secondary datasource (H2-DB): Lưu các thực thể liên quan đến session
- Primary datasource (MariaDB): Lưu các thực thể còn lại
