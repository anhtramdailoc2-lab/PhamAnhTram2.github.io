<style>
    * {
        box-sizing: border-box;
    }

    body {
        font-family: 'Arial', sans-serif;
        color: #2c3e50;
        line-height: 1.5;
        margin: 0;
        padding: 0;
        font-size: 10pt;
    }

    /* Header Section */
    .header-container {
        display: table;
        width: 100%;
        border-bottom: 2px solid #2c3e50;
        padding-bottom: 15px;
        margin-bottom: 18px;
    }

    .header-left {
        display: table-cell;
        width: 75%;
        vertical-align: middle;
    }

    .header-right {
        display: table-cell;
        width: 25%;
        vertical-align: middle;
        text-align: right;
    }

    .avatar {
        width: 110px;
        height: 150px;
        object-fit: cover;
        border-radius: 4px;
        border: 1px solid #cbd5e0;
    }

    .name {
        font-size: 22pt;
        font-weight: bold;
        color: #1a365d;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        margin: 0 0 4px 0;
    }

    .title {
        font-size: 12pt;
        color: #4a5568;
        font-weight: bold;
        margin: 0 0 12px 0;
    }

    .contact-grid {
        display: table;
        width: 100%;
        margin-top: 8px;
    }

    .contact-row {
        display: table-row;
    }

    .contact-item {
        display: table-cell;
        width: 50%;
        font-size: 9.5pt;
        color: #4a5568;
        padding-bottom: 4px;
    }

    /* Section Styling */
    .section-title {
        font-size: 12pt;
        font-weight: bold;
        color: #1a365d;
        text-transform: uppercase;
        border-left: 4px solid #1a365d;
        padding-left: 8px;
        margin-top: 18px;
        margin-bottom: 10px;
    }

    p.objective {
        text-align: justify;
        margin: 0 0 12px 0;
    }

    /* Experience & Education Block */
    .block {
        margin-bottom: 12px;
    }

    .block-header {
        display: table;
        width: 100%;
        font-weight: bold;
        color: #2d3748;
        margin-bottom: 4px;
    }

    .block-title {
        display: table-cell;
        text-align: left;
    }

    .block-date {
        display: table-cell;
        text-align: right;
        font-weight: normal;
        color: #718096;
        font-size: 9pt;
    }

    .block-subtitle {
        font-style: italic;
        color: #4a5568;
        margin-bottom: 6px;
    }

    ul {
        margin: 0;
        padding-left: 18px;
    }

    li {
        margin-bottom: 4px;
        text-align: justify;
    }

    /* Skills Layout */
    .skills-table {
        display: table;
        width: 100%;
        margin-top: 4px;
    }

    .skills-row {
        display: table-row;
    }

    .skills-cell-title {
        display: table-cell;
        width: 30%;
        font-weight: bold;
        color: #2d3748;
        padding-bottom: 8px;
        vertical-align: top;
    }

    .skills-cell-desc {
        display: table-cell;
        width: 70%;
        padding-bottom: 8px;
        vertical-align: top;
        text-align: justify;
    }

    .skill-tag {
        display: inline-block;
        background-color: #edf2f7;
        color: #2b6cb0;
        padding: 2px 8px;
        border-radius: 4px;
        font-size: 8.5pt;
        font-weight: bold;
        margin-right: 4px;
        margin-bottom: 4px;
    }
</style>

<div class="header-container">
    <div class="header-left">
        <h1 class="name">NGUYỄN VĂN A</h1>
        <p class="title">CHUYÊN VIÊN LẬP TRÌNH PHP/LARAVEL</p>
        <div class="contact-grid">
            <div class="contact-row">
                <div class="contact-item">📞 (+84) 123 456 789</div>
                <div class="contact-item">📧 angyenvana@email.com</div>
            </div>
            <div class="contact-row">
                <div class="contact-item">📍 TP. Hồ Chí Minh</div>
                <div class="contact-item">🌐 linkedin.com/in/angyenvana</div>
            </div>
        </div>
    </div>
    <div class="header-right">
        <img src="path/to/your/avatar.jpg" alt="Avatar" class="avatar">
    </div>
</div>

<div class="section-title">MỤC TIÊU NGHỀ NGHIỆP</div>
<p class="objective">
    Mong muốn trở thành một lập trình viên PHP chuyên nghiệp, cống hiến cho sự phát triển của công ty và nâng cao kỹ năng bản thân. 
    Khao khát học hỏi công nghệ mới và áp dụng kiến thức vào thực tế để tạo ra những sản phẩm chất lượng.
</p>

<div class="section-title">KINH NGHIỆM LÀM VIỆC</div>
<div class="block">
    <div class="block-header">
        <div class="block-title">Lập trình viên PHP/Laravel</div>
        <div class="block-date">01/2021 - Hiện tại</div>
    </div>
    <div class="block-subtitle">Công ty ABC, TP. HCM</div>
    <ul>
        <li>Tham gia phát triển hệ thống E-commerce dựa trên Laravel Framework.</li>
        <li>Xây dựng RESTful API cho ứng dụng di động.</li>
        <li>Tối ưu hóa hiệu suất website và cơ sở dữ liệu MySQL.</li>
        <li>Phối hợp với nhóm frontend và design để triển khai các tính năng mới.</li>
    </ul>
</div>

<div class="section-title">HỌC VẤN</div>
<div class="block">
    <div class="block-header">
        <div class="block-title">Cử nhân Công nghệ thông tin</div>
        <div class="block-date">09/2017 - 12/2020</div>
    </div>
    <div class="block-subtitle">Đại học Khoa học Tự nhiên TP.HCM</div>
</div>

<div class="section-title">KỸ NĂNG</div>
<div class="skills-table">
    <div class="skills-row">
        <div class="skills-cell-title">Ngôn ngữ</div>
        <div class="skills-cell-desc">
            <span class="skill-tag">PHP</span>
            <span class="skill-tag">JavaScript</span>
            <span class="skill-tag">HTML/CSS</span>
        </div>
    </div>
    <div class="skills-row">
        <div class="skills-cell-title">Frameworks</div>
        <div class="skills-cell-desc">
            <span class="skill-tag">Laravel</span>
            <span class="skill-tag">Vue.js</span>
            <span class="skill-tag">Tailwind CSS</span>
        </div>
    </div>
    <div class="skills-row">
        <div class="skills-cell-title">Cơ sở dữ liệu</div>
        <div class="skills-cell-desc">
            <span class="skill-tag">MySQL</span>
            <span class="skill-tag">PostgreSQL</span>
        </div>
    </div>
</div>
