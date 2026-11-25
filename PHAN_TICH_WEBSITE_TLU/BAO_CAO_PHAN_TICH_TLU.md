BÁO CÁO PHÂN TÍCH WEBSITE TRƯỜNG ĐẠI HỌC THỦY LỢI (tlu.edu.vn) VÀ KIẾN TRÚC FRONT-END 3 LỚP
PHẦN I: ĐÁNH GIÁ TOÀN DIỆN UI/UX VÀ CẤU TRÚC WEBSITE
1. Tổng quan website
Website chính thức của Trường Đại học Thủy Lợi ([https://tlu.edu.vn/](https://tlu.edu.vn/)) đóng vai trò là cổng thông tin điện tử trung tâm, kết nối nhà trường với toàn bộ hệ sinh thái giáo dục và xã hội.

Mục đích hoạt động: Cung cấp thông tin chính thống về chiến lược phát triển, hoạt động đào tạo, tuyển sinh, nghiên cứu khoa học, hợp tác quốc tế và các sự kiện nổi bật của nhà trường.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Đối tượng người dùng chính:

Thí sinh và phụ huynh: Tìm kiếm thông tin tuyển sinh, ngành đào tạo, điểm chuẩn và môi trường học tập.

Sinh viên và học viên cao học: Theo dõi thông báo học vụ, lịch sự kiện, hoạt động đoàn thể và cơ hội việc làm.

Cán bộ, giảng viên và nhà nghiên cứu: Cập nhật hoạt động khoa học công nghệ, hợp tác quốc tế và tin tức nội bộ.

Đối tác doanh nghiệp và cựu sinh viên: Kết nối tuyển dụng, chuyển giao công nghệ và mạng lưới cựu sinh viên.

Các chức năng chính ghi nhận trên giao diện trang chủ:

Hệ thống điều hướng đa cấp theo nhóm đối tượng và lĩnh vực hoạt động (Giới thiệu, Tin tức & Thông báo, Tuyển sinh, Đào tạo, Khoa học công nghệ, Hợp tác đối ngoại, Sinh viên, Cựu sinh viên).

Thanh tìm kiếm thông tin toàn trang và công cụ chuyển đổi ngôn ngữ (Việt/Anh) ở góc trên bên phải.

Trình chiếu banner sự kiện trọng điểm (Hero Banner).

Phân luồng tin tức theo chuyên mục: Tin tức – Thông báo, Sự kiện, Tuyển sinh, Đào tạo – Sinh viên – Cựu sinh viên, Hợp tác quốc tế, Nghiên cứu, Vì cộng đồng.

Trình bày tương tác danh sách các đơn vị đào tạo/khoa kèm hình ảnh trực quan và thư viện hình ảnh nổi bật.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
Nhóm người dùng	Vai trò cốt lõi của website	Khu vực tiếp cận ưu tiên trên trang chủ
Sinh viên	Kênh cập nhật thông báo học vụ, hoạt động ngoại khóa, cơ hội tuyển dụng và biểu mẫu hành chính.	
Mục Thông báo, Sự kiện, Sinh viên, thanh điều hướng nhanh. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Giảng viên & Cán bộ	Cổng thông tin học thuật, công bố đề tài nghiên cứu, hợp tác quốc tế và thông tin các khoa/viện.	
Mục Nghiên cứu, Hợp tác quốc tế, Các đơn vị đào tạo, khoa. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Người ngoài trường (Thí sinh, Đối tác)	Kênh nhận diện thương hiệu, tra cứu thông tin tuyển sinh, uy tín đào tạo và đầu mối liên hệ.	
Hero Banner, Những con số ấn tượng, Tuyển sinh, Mạng lưới đối tác, Footer. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

2. Phân tích giao diện người dùng (UI)
Màu sắc chủ đạo: Website sử dụng tông xanh dương đậm (#002B80 – #003399) làm màu thương hiệu chủ đạo trên nền trắng (#FFFFFF) và xám nhạt (#F4F6F9). Sự tương phản giữa nền xanh đậm và chữ trắng tạo cảm giác nghiêm túc, chuẩn mực của một cơ sở giáo dục đại học công lập kỹ thuật – kinh tế, đồng thời gợi liên tưởng trực tiếp đến đặc thù ngành Thủy lợi.

Bố cục và cách sắp xếp nội dung: Trang chủ áp dụng bố cục dàn trang theo chiều dọc (Single-page vertical sections), xen kẽ nhịp điệu giữa các khối nền trắng (Tin tức, Sự kiện, Hợp tác, Nghiên cứu) và các khối nền xanh toàn chiều rộng (Navigation, Banner trung tâm, Các đơn vị đào tạo, Mạng lưới đối tác, Footer) để phân tách thị giác rõ ràng giữa các nhóm nội dung.

Font chữ, hình ảnh, banner và biểu tượng:

Typography: Sử dụng font chữ không chân (Sans-serif) hiện đại; tiêu đề từng chuyên mục lớn được viết in hoa, căn giữa, màu xanh thương hiệu giúp người đọc dễ nhận diện ranh giới từng phần.

Hình ảnh & Banner: Hero Banner có thiết kế đồ họa nhận diện thương hiệu rõ nét (kỷ niệm 20/11 và bộ nhận diện mới của trường). Tuy nhiên, ảnh chụp toàn trang cho thấy nhiều khung ảnh ở nửa dưới trang (Tuyển sinh, Đào tạo, Hợp tác quốc tế, Nghiên cứu, Hình ảnh nổi bật) đang hiển thị ở trạng thái khung xám placeholder do cơ chế tải chậm (lazy-loading) chưa kịp nạp ảnh khi cuộn nhanh.

Biểu tượng (Icons): Sử dụng hệ thống icon đơn giản (icon ngôi nhà tại menu Trang chủ, kính lúp tìm kiếm, icon định vị/điện thoại tại Footer, dấu chấm điều hướng slider).

Tính nhất quán trong thiết kế: Website đạt độ nhất quán cao ở các chuyên mục tin tức chuyên sâu. Cụ thể, ba khối Hợp tác quốc tế, Nghiên cứu và Vì cộng đồng đều dùng chung một mẫu thiết kế (3 thẻ bài viết có ảnh bên trái + 1 cột danh sách tin text bên phải), giúp giảm tải nhận thức cho người dùng khi duyệt trang.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
3. Phân tích trải nghiệm người dùng (UX)
Khả năng tìm kiếm thông tin: Thanh tìm kiếm đặt cố định ở góc trên bên phải của Header giúp người dùng dễ dàng tra cứu từ khóa ngay khi vào trang. Bên cạnh đó, việc tách biệt cột Tin tức (có hình ảnh) và Thông báo (dạng danh sách văn bản súc tích) ngay đầu trang giúp sinh viên quét nhanh các thông báo quan trọng mà không bị phân tâm bởi hình ảnh.

Cách tổ chức menu và điều hướng: Thanh điều hướng chính trải ngang với khoảng 8–9 mục lớn bao phủ toàn bộ hoạt động của nhà trường. Cách phân nhóm theo đối tượng (Sinh viên, Cựu sinh viên) song song với phân nhóm theo chức năng (Tuyển sinh, Đào tạo, Khoa học công nghệ) phản ánh đúng nhu cầu thực tế của cổng thông tin đại học.

Trải nghiệm sử dụng của sinh viên: Sinh viên dễ dàng tiếp cận tin tức tuyển dụng, hoạt động phong trào và thông báo mới ngay màn hình đầu tiên sau Hero Banner. Tuy nhiên, trên trang chủ chưa làm nổi bật cụm nút truy cập nhanh (Quick Links) dẫn thẳng tới các hệ thống tác nghiệp hằng ngày như Cổng thông tin sinh viên (đăng ký tín chỉ), Thư viện số, hay Hệ thống học trực tuyến (LMS).

Những điểm thuận tiện và bất tiện:

Thuận tiện: Phân tầng thông tin mạch lạc từ tổng quan đến chi tiết; tiêu đề khối rõ ràng; danh sách các khoa/viện có khu vực hiển thị tương tác trực tiếp ngay trên trang chủ.

Bất tiện: Trang chủ quá dài (12 phân khu nội dung nối tiếp nhau), dẫn đến tình trạng mỏi mắt khi cuộn trang (scroll fatigue) và làm chậm quá trình hiển thị hình ảnh ở các phần phía dưới.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
4. Phân tích cấu trúc website
Header và thanh điều hướng: Gồm 2 tầng rõ rệt: tầng trên chứa logo, tên trường, ô tìm kiếm và nút chọn ngôn ngữ; tầng dưới là thanh menu chính nền xanh đậm trải rộng toàn màn hình.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Các khu vực nội dung trên trang chủ (từ trên xuống dưới):

Hero Banner: Truyền thông sự kiện và nhận diện thương hiệu.

Tin tức & Thông báo: Tỷ lệ 2 cột tin tức bên trái : 1 cột thông báo bên phải.

Sự kiện: Dải 4 thẻ sự kiện ngang kèm thanh điều hướng slide.

Những con số ấn tượng: Dải 5 chỉ số thống kê nổi bật.

Banner/Khối nhấn nền xanh toàn chiều rộng: Phân tách nhóm thông tin chung với nhóm đào tạo.

Tuyển sinh: Bố cục chia đôi (hình ảnh bên trái, thông tin tóm tắt + nút hành động bên phải).

Đào tạo – Sinh viên – Cựu sinh viên: Bố cục 3 cột ngang song song.

Các đơn vị đào tạo, khoa: Bố cục chia đôi 50%–50% (danh sách khoa bên trái, ảnh minh họa và nút liên kết bên phải).

Hợp tác quốc tế, Nghiên cứu, Vì cộng đồng: Ba phân khu chuyên đề dùng chung cấu trúc lưới 4 cột.

Mạng lưới đối tác: Khối nền xanh giới thiệu và dải khung trắng trưng bày logo đối tác.

Hình ảnh nổi bật: Lưới ảnh dạng Bento bất đối xứng gồm 1 ảnh lớn ở trung tâm và 14 ảnh nhỏ bao quanh.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
Footer: Chia thành 3 tầng: tầng thông tin địa chỉ các cơ sở đào tạo, tầng 4 cột liên kết nhanh kết hợp khung bản đồ/fanpage, và dòng bản quyền ở đáy trang.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Phân biệt nội dung đã kiểm chứng và chưa thể kiểm chứng từ dữ liệu đầu vào:

Đã kiểm chứng trực tiếp qua ảnh chụp trang chủ: Cấu trúc bố cục 12 phân khu, bảng màu nhận diện, phân bổ tỷ lệ cột, trạng thái hiển thị ban đầu của bộ đếm số (0+, 0%) và cơ chế lazy-loading của các khung ảnh.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Chưa thể kiểm chứng từ ảnh chụp tĩnh (cần kiểm tra trực tiếp trên trình duyệt/DOM): Hiệu ứng xổ xuống (dropdown/mega-menu) của thanh điều hướng, tốc độ chuyển slide của Hero Banner, dữ liệu số thực tế sau khi chạy hiệu ứng counter-up, tốc độ phản hồi máy chủ (TTFB) và giao diện thực tế trên màn hình điện thoại (Mobile viewport).

5. Đánh giá ưu điểm và hạn chế
Tiêu chí	Ưu điểm nổi bật (Kèm dẫn chứng)	Hạn chế cần khắc phục (Kèm dẫn chứng)
Bố cục & Thị giác	
Hệ thống lưới (Grid) đồng bộ ở các mục Hợp tác quốc tế, Nghiên cứu, Vì cộng đồng; khoảng trắng hợp lý giúp trang không bị rối dù lượng tin lớn. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Trang chủ dàn trải quá nhiều phân khu (12 sections), khiến các thông tin quan trọng ở nửa dưới dễ bị người dùng bỏ qua. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Hiệu năng hiển thị	
Áp dụng kỹ thuật lazy-loading giúp giảm tải băng thông ban đầu khi người dùng mới truy cập vào đầu trang. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Ngưỡng kích hoạt lazy-load chưa tối ưu: khi cuộn trang hoặc chụp toàn trang, hàng loạt khung ảnh từ mục Tuyển sinh đến Hình ảnh nổi bật vẫn là ô xám trống; khối xanh dưới mục thống kê chưa hiển thị nội dung. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Tương tác dữ liệu	
Có khu vực Những con số ấn tượng trực quan hóa thành tựu và khu vực chọn khoa/viện tương tác trực tiếp. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Các chỉ số thống kê hiển thị mặc định là 0+ và 0% khi chưa kích hoạt sự kiện cuộn, gây hụt hẫng về mặt thông tin nếu JavaScript chạy chậm hoặc lỗi. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Điều hướng sinh viên	
Tách riêng mục Thông báo dạng văn bản súc tích ngay cạnh Tin tức giúp sinh viên nắm bắt lịch trình nhanh chóng. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Thiếu cụm phím tắt (Quick Access Bar) dẫn tới Cổng sinh viên, Đăng ký học và Tra cứu điểm ngay vùng đầu trang. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

6. Đề xuất cải thiện
Về giao diện (UI): Bổ sung thanh truy cập nhanh (Quick Links) ngay dưới Hero Banner với các icon rõ ràng dẫn đến Cổng thông tin sinh viên, Tuyển sinh, Thư viện, E-Learning để rút ngắn thao tác tìm kiếm.

Về trải nghiệm người dùng (UX): Gộp hoặc thu gọn các phân khu tin tức có cấu trúc trùng lặp (Hợp tác quốc tế, Nghiên cứu, Vì cộng đồng) thành giao diện dạng Tab chuyển đổi trên cùng một khối nhằm giảm 30–40% chiều dài cuộn trang chủ.

Về khả năng tương thích điện thoại (Responsive): Trên màn hình nhỏ, chuyển lưới 4 cột tin tức và lưới ảnh Bento 5×4 sang dạng trượt ngang (horizontal swipe carousel) hoặc lưới 1–2 cột để tránh việc người dùng phải cuộn quá dài trên thiết bị di động.

Về tốc độ tải trang và hiệu năng (Performance):

Điều chỉnh rootMargin của IntersectionObserver (ví dụ 200px) để hình ảnh được tải trước khi người dùng cuộn tới vùng nhìn thấy, loại bỏ hiện tượng khung xám trống.

Đặt giá trị thống kê thực tế ngay trong mã nguồn HTML ban đầu (ví dụ 65+, 95%) thay vì 0+, sau đó dùng JavaScript chạy hiệu ứng đếm số tăng dần để đảm bảo tính toàn vẹn nội dung ngay cả khi script chưa chạy.

Về khả năng tiếp cận thông tin (Accessibility): Bổ sung thuộc tính alt mô tả đầy đủ cho toàn bộ ảnh tin tức, tăng độ tương phản cho các mục khoa không được chọn (inactive items) trong khối nền xanh Các đơn vị đào tạo, khoa.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Về tổ chức nội dung: Đưa khối Tuyển sinh và Đào tạo lên vị trí cao hơn trong mùa tuyển sinh cao điểm, đồng thời gắn nhãn phân loại (badge) cho từng mục thông báo (ví dụ: [Đào tạo], [Công tác sinh viên], [Học bổng]).

7. Đánh giá tổng thể và lộ trình ưu tiên cải tiến
Website Trường Đại học Thủy Lợi (tlu.edu.vn) đáp ứng tốt chức năng của một cổng thông tin đại học quy mô lớn với cấu trúc phân mục bài bản, nhận diện thương hiệu rõ ràng và tính nhất quán cao trong thiết kế hệ thống thẻ tin. Để nâng cao trải nghiệm thực tế, nhà trường nên ưu tiên cải tiến theo 3 bước: (1) Tối ưu cơ chế tải ảnh lazy-loading và giá trị khởi tạo của bộ đếm thống kê để khắc phục tình trạng hiển thị khung trống; (2) Bổ sung thanh truy cập nhanh các dịch vụ số cho sinh viên ngay đầu trang; và (3) Tinh gọn chiều dài trang chủ thông qua cơ chế Tab hóa các chuyên mục tin tức có cùng định dạng.   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

PHẦN II: PHÂN TÍCH KIẾN TRÚC FRONT-END THEO 3 LỚP SONG SONG
BƯỚC 1 — XÁC ĐỊNH CẤU TRÚC TỔNG THỂ TRANG CHỦ
Quan sát từ ngoài vào trong và từ trên xuống dưới, toàn bộ trang chủ tlu.edu.vn được chia thành các vùng bố cục lớn như sau:   
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Plaintext
page
├── site-header
│   ├── header-top (Container căn giữa)
│   └── main-nav (Full-width nền xanh, nội dung bên trong căn giữa)
├── hero-banner (Full-width)
├── main-content
│   ├── news-announcement-section (Container căn giữa)
│   ├── events-section (Container căn giữa)
│   ├── statistics-section (Container căn giữa)
│   ├── highlight-banner-section (Full-width nền xanh)
│   ├── admissions-section (Container căn giữa)
│   ├── academic-triad-section (Container căn giữa)
│   ├── faculties-section (Full-width chia đôi 50% - 50%)
│   ├── international-section (Container căn giữa)
│   ├── research-section (Container căn giữa)
│   ├── partners-section (Full-width nền xanh, nội dung căn giữa)
│   ├── community-section (Container căn giữa)
│   └── gallery-section (Container căn giữa)
└── site-footer (Full-width nền xanh, nội dung căn giữa)
Vùng lớn (Layout Region)	Vai trò	Phạm vi & Quan hệ với vùng cha (page)	Container căn giữa (.container)
site-header	
Chứa nhận diện thương hiệu, tìm kiếm và menu điều hướng chính. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Nằm trên cùng của page, rộng 100%.	Có (giới hạn chiều rộng nội dung bên trong 1200px–1280px).
hero-banner	
Trình bày banner truyền thông sự kiện trọng điểm. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Con trực tiếp của page, nằm ngay dưới site-header, rộng 100%.	Không (ảnh banner tràn viền toàn màn hình).
main-content	
Bao bọc toàn bộ 12 phân khu nội dung chính của trang. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Con trực tiếp của page, xếp dọc theo Normal Flow.	Từng section con bên trong tự chứa .container riêng để giữ màu nền tràn viền.
site-footer	
Chứa địa chỉ các cơ sở, liên kết nhanh, bản đồ/fanpage và bản quyền. 
Screenshot_25-11-2026_143641_tlu.edu.vn.jpg

Nằm dưới cùng của page, rộng 100% với nền xanh đậm.	Có (căn giữa 3 tầng nội dung bên trong).
BƯỚC 2 — PHÂN TÍCH TỪNG COMPONENT THEO 3 LỚP SONG SONG
1. Header & Thanh điều hướng (site-header)
1. Nhận diện Layout Box

Plaintext
site-header
├── header-top
│   └── container
│       ├── brand-box (logo + tên trường)
│       └── header-tools (search-form + language-switch)
└── main-nav
    └── container
        └── nav-list
            └── nav-item (×9)
Giải thích: site-header là hộp cha bao bọc toàn bộ phần đầu trang. Do phần trên có nền trắng chứa logo/tìm kiếm, còn phần dưới có nền xanh đậm chứa menu, ta tách thành 2 hộp con xếp dọc là header-top và main-nav.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Kết hợp Normal Flow (xếp dọc 2 tầng header-top và main-nav) và Flexbox (dàn hàng ngang bên trong mỗi tầng).

Flexbox 1 (.header-top .container):

Flex Container: .header-top .container

Flex Items: .brand-box, .header-tools

Thuộc tính cần thiết: display: flex; justify-content: space-between; align-items: center; gap: 24px; (đẩy logo sang trái, công cụ tìm kiếm sang phải).

Flexbox 2 (.nav-list):

Flex Container: .nav-list

Flex Items: .nav-item

Thuộc tính cần thiết: display: flex; justify-content: space-between; align-items: center; gap: 16px;

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Khu vực đầu trang	Phần đầu của website	header
Logo & tên trường	Liên kết về trang chủ	a, img, span (hoặc p)
Ô nhập từ khóa & nút tìm	Biểu mẫu tìm kiếm	form, input, button
Thanh menu chính	Điều hướng toàn trang	nav, ul, li, a
4. Phiên bản chỉ dùng div

HTML
<div class="site-header">
    <div class="header-top">
        <div class="container">
            <div class="brand-box">
                <div class="logo">TLU</div>
                <div class="school-name">TRƯỜNG ĐẠI HỌC THỦY LỢI</div>
            </div>
            <div class="header-tools">
                <div class="search-box">Tìm kiếm...</div>
                <div class="lang-switch">EN</div>
            </div>
        </div>
    </div>
    <div class="main-nav">
        <div class="container">
            <div class="nav-list">
                <div class="nav-item">Giới thiệu</div>
                <div class="nav-item">Tin tức & Thông báo</div>
                <div class="nav-item">Tuyển sinh</div>
                <div class="nav-item">Đào tạo</div>
            </div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<header class="site-header">
    <div class="header-top">
        <div class="container">
            <a href="/" class="brand-box">
                <img src="logo-tlu.png" alt="Logo Trường Đại học Thủy Lợi">
                <span>TRƯỜNG ĐẠI HỌC THỦY LỢI</span>
            </a>
            <div class="header-tools">
                <form class="search-form" action="/search">
                    <input type="search" placeholder="Tìm kiếm...">
                    <button type="submit" aria-label="Tìm kiếm">🔍</button>
                </form>
                <a href="/en" class="lang-switch">EN</a>
            </div>
        </div>
    </div>
    <nav class="main-nav" aria-label="Điều hướng chính">
        <div class="container">
            <ul class="nav-list">
                <li><a href="/">Trang chủ</a></li>
                <li><a href="/gioi-thieu">Giới thiệu</a></li>
                <li><a href="/tin-tuc">Tin tức & Thông báo</a></li>
                <li><a href="/tuyen-sinh">Tuyển sinh</a></li>
                <li><a href="/dao-tao">Đào tạo</a></li>
            </ul>
        </div>
    </nav>
</header>
6. CSS Layout minh họa

CSS
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 16px;
}

.header-top .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 24px;
}

.brand-box,
.header-tools,
.nav-list {
    display: flex;
    align-items: center;
    gap: 16px;
}

.nav-list {
    justify-content: space-between;
    list-style: none;
    margin: 0;
    padding: 0;
}
7. Kết luận tư duy

Layout: site-header → header-top + main-nav

CSS: Block flow (2 tầng) + Flexbox row (căn ngang bên trong mỗi tầng)

HTML: header → a (img + span) + form (input + button) + nav (ul > li > a)

2. Hero Banner (hero-banner)
1. Nhận diện Layout Box

Plaintext
hero-banner
├── hero-slide-list
│   └── hero-slide
│       └── hero-image
└── hero-controls (các nút điều hướng nổi ở mép phải)
Giải thích: hero-banner chiếm toàn bộ chiều ngang màn hình để tạo điểm nhấn thị giác đầu tiên. Cụm nút điều hướng nhỏ nằm đè lên mép phải của ảnh nên cần một hộp riêng định vị nổi. (Lưu ý: Có khả năng là carousel nhiều slide, cần kiểm tra HTML/JS thực tế để xác nhận).


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Block Flow kết hợp CSS Position (relative / absolute).

Mốc định vị: .hero-banner đặt position: relative; làm khung tham chiếu; .hero-controls đặt position: absolute; right: 16px; top: 50%; transform: translateY(-50%); để ghim cụm nút điều hướng vào cạnh phải của banner.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Vùng banner chính	Vùng giới thiệu nổi bật đầu trang	section
Ảnh banner sự kiện	Hình ảnh truyền thông chính	img (bên trong a nếu bấm được)
Các nút chuyển slide	Thao tác điều khiển giao diện	button
4. Phiên bản chỉ dùng div

HTML
<div class="hero-banner">
    <div class="hero-slide">
        <div class="hero-image">Banner Chào mừng 20/11 & Nhận diện thương hiệu</div>
    </div>
    <div class="hero-controls">
        <div class="control-dot"></div>
        <div class="control-dot"></div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="hero-banner" aria-label="Banner nổi bật">
    <a href="/nhan-dien-thuong-hieu" class="hero-slide">
        <img src="banner-20-11.jpg" alt="Lễ kỷ niệm Ngày Nhà giáo Việt Nam 20/11 và Ra mắt nhận diện thương hiệu">
    </a>
    <div class="hero-controls">
        <button type="button" aria-label="Slide 1"></button>
        <button type="button" aria-label="Slide 2"></button>
    </div>
</section>
6. CSS Layout minh họa

CSS
.hero-banner {
    position: relative;
    width: 100%;
}

.hero-banner img {
    display: block;
    width: 100%;
    height: auto;
}

.hero-controls {
    position: absolute;
    right: 16px;
    top: 50%;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    gap: 8px;
}
7. Kết luận tư duy

Layout: hero-banner → hero-slide + hero-controls

CSS: Block + position: relative / position: absolute

HTML: section → a (img) + div (button)

3. Section Tin tức & Thông báo (news-announcement-section)
1. Nhận diện Layout Box

Plaintext
news-announcement-section
└── container (Flex Container tỷ lệ 2 : 1)
    ├── news-column (Cột trái - chiếm 2 phần)
    │   ├── section-title ("TIN TỨC")
    │   └── news-grid (Flex Container chia 2 cột con)
    │       ├── featured-news-card (1 bài lớn bên trái)
    │       └── secondary-news-list (2 bài nhỏ xếp dọc bên phải)
    └── announcement-column (Cột phải - chiếm 1 phần)
        ├── section-title ("THÔNG BÁO")
        └── announcement-list (6 mục thông báo xếp dọc)
Giải thích: Đây là bố cục lồng nhau 2 cấp: cấp ngoài chia màn hình thành cột Tin tức rộng gấp đôi cột Thông báo; cấp trong của cột Tin tức tiếp tục chia thành 1 tin nổi bật bên trái và 2 tin phụ xếp dọc bên phải.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Nested Flexbox (Flexbox lồng nhau) hoặc CSS Grid.

Cấp 1 (.news-announcement-section .container):

Flex Container: .container

Flex Items: .news-column (flex: 2;) và .announcement-column (flex: 1;) → tạo tỷ lệ chuẩn 2 : 1.

Thuộc tính cần thiết: display: flex; gap: 32px; align-items: flex-start;

Cấp 2 (.news-grid):

Flex Container: .news-grid

Flex Items: .featured-news-card (flex: 1.2;) và .secondary-news-list (flex: 1;).

Bên trong .secondary-news-list và .announcement-list xếp dọc theo Normal Flow (hoặc display: flex; flex-direction: column; gap: 16px;).

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Vùng Tin tức & Thông báo	Phân khu nội dung lớn	section
Tiêu đề "TIN TỨC", "THÔNG BÁO"	Tiêu đề phân khu	h2
Mỗi thẻ bài viết tin tức	Bài viết độc lập	article
Ảnh đại diện bài viết	Hình ảnh minh họa tin	img
Tiêu đề bài viết / thông báo	Tiêu đề cấp thẻ + liên kết	h3 > a
Đoạn trích dẫn ngắn	Mô tả tóm tắt	p
Ngày đăng tin	Dữ liệu thời gian	time
4. Phiên bản chỉ dùng div

HTML
<div class="news-announcement-section">
    <div class="container">
        <div class="news-column">
            <div class="section-title">TIN TỨC</div>
            <div class="news-grid">
                <div class="featured-news-card">
                    <div class="news-thumb">Ảnh tin lớn</div>
                    <div class="news-title">Tiêu đề tin nổi bật</div>
                    <div class="news-excerpt">Mô tả ngắn...</div>
                </div>
                <div class="secondary-news-list">
                    <div class="small-news-card">Tin phụ 1</div>
                    <div class="small-news-card">Tin phụ 2</div>
                </div>
            </div>
        </div>
        <div class="announcement-column">
            <div class="section-title">THÔNG BÁO</div>
            <div class="announcement-list">
                <div class="announcement-item">Thông báo 1</div>
                <div class="announcement-item">Thông báo 2</div>
            </div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="news-announcement-section">
    <div class="container">
        <div class="news-column">
            <h2 class="section-title">TIN TỨC</h2>
            <div class="news-grid">
                <article class="featured-news-card">
                    <a href="/tin-1"><img src="tuyen-dung.jpg" alt="Thông báo tuyển dụng"></a>
                    <h3><a href="/tin-1">Tiêu đề bài viết tin tức nổi bật</a></h3>
                    <p>Đoạn mô tả tóm tắt nội dung bài viết...</p>
                    <time datetime="2026-11-20">20/11/2026</time>
                </article>
                <div class="secondary-news-list">
                    <article class="small-news-card">
                        <a href="/tin-2"><img src="tin-2.jpg" alt="Tin phụ 1"></a>
                        <h3><a href="/tin-2">Tiêu đề tin phụ 1</a></h3>
                        <time datetime="2026-11-19">19/11/2026</time>
                    </article>
                    <article class="small-news-card">
                        <a href="/tin-3"><img src="tin-3.jpg" alt="Tin phụ 2"></a>
                        <h3><a href="/tin-3">Tiêu đề tin phụ 2</a></h3>
                        <time datetime="2026-11-18">18/11/2026</time>
                    </article>
                </div>
            </div>
        </div>
        <aside class="announcement-column">
            <h2 class="section-title">THÔNG BÁO</h2>
            <ul class="announcement-list">
                <li>
                    <a href="/tb-1">Thông báo về kế hoạch đăng ký học phần</a>
                    <time datetime="2026-11-20">20/11/2026</time>
                </li>
                <li>
                    <a href="/tb-2">Thông báo xét cấp học bổng khuyến khích học tập</a>
                    <time datetime="2026-11-19">19/11/2026</time>
                </li>
            </ul>
        </aside>
    </div>
</section>
6. CSS Layout minh họa

CSS
.news-announcement-section .container {
    display: flex;
    gap: 32px;
    align-items: flex-start;
}

.news-column {
    flex: 2;
}

.announcement-column {
    flex: 1;
}

.news-grid {
    display: flex;
    gap: 20px;
}

.featured-news-card {
    flex: 1.2;
}

.secondary-news-list {
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 16px;
}
7. Kết luận tư duy

Layout: container → news-column (2) + announcement-column (1)

CSS: Nested Flexbox (flex: 2 vs flex: 1) + Flex column cho danh sách dọc

HTML: section → div (h2 + article) + aside (h2 + ul > li > a, time)

4. Section Sự kiện (events-section)
1. Nhận diện Layout Box

Plaintext
events-section
└── container
    ├── section-title ("SỰ KIỆN")
    ├── event-list (Hàng ngang 4 thẻ)
    │   └── event-card (×4: image + title + meta)
    └── slider-pagination (Dãy chấm tròn điều hướng)
Giải thích: Tiêu đề nằm trên cùng, dải 4 thẻ sự kiện xếp ngang bằng nhau ở giữa, và thanh chấm phân trang nằm căn giữa bên dưới.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: CSS Grid (hoặc Flexbox) cho hàng 4 thẻ sự kiện.

Lựa chọn CSS Grid: Vì 4 thẻ sự kiện có độ rộng bằng nhau tuyệt đối (4 cột đều nhau), dùng display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px; giúp kiểm soát độ rộng cột chính xác hơn mà không cần tính phần trăm trừ gap.

Thanh pagination: Dùng display: flex; justify-content: center; gap: 8px;.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tiêu đề "SỰ KIỆN"	Tiêu đề phân khu	h2
Mỗi thẻ sự kiện	Nội dung sự kiện độc lập	article
Banner sự kiện	Hình ảnh sự kiện	img
Tên sự kiện	Tiêu đề thẻ + liên kết	h3 > a
Nút chấm chuyển trang	Điều khiển slider	button
4. Phiên bản chỉ dùng div

HTML
<div class="events-section">
    <div class="container">
        <div class="section-title">SỰ KIỆN</div>
        <div class="event-list">
            <div class="event-card">Sự kiện 1</div>
            <div class="event-card">Sự kiện 2</div>
            <div class="event-card">Sự kiện 3</div>
            <div class="event-card">Sự kiện 4</div>
        </div>
        <div class="slider-pagination">
            <div class="dot"></div>
            <div class="dot"></div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="events-section">
    <div class="container">
        <h2 class="section-title">SỰ KIỆN</h2>
        <div class="event-list">
            <article class="event-card">
                <a href="/su-kien-1"><img src="sk1.jpg" alt="Sự kiện 1"></a>
                <h3><a href="/su-kien-1">Tên sự kiện nổi bật 1</a></h3>
                <time datetime="2026-11-15">15/11/2026</time>
            </article>
            <!-- Lặp lại 3 thẻ article tương tự -->
        </div>
        <div class="slider-pagination">
            <button type="button" aria-label="Trang 1"></button>
            <button type="button" aria-label="Trang 2"></button>
        </div>
    </div>
</section>
6. CSS Layout minh họa

CSS
.event-list {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.slider-pagination {
    display: flex;
    justify-content: center;
    gap: 8px;
    margin-top: 20px;
}
7. Kết luận tư duy

Layout: events-section → h2 + event-list (4 cards) + slider-pagination

CSS: CSS Grid (repeat(4, 1fr)) + Flexbox center cho pagination

HTML: section → h2 + article (a, img, h3, time) + button

5. Section Những con số ấn tượng (statistics-section)
1. Nhận diện Layout Box

Plaintext
statistics-section
└── container
    ├── section-title ("NHỮNG CON SỐ ẤN TƯỢNG")
    └── stats-list (Hàng ngang 5 cột thống kê)
        └── stat-item (×5: stat-number + stat-label)
Giải thích: Gồm 5 cột số liệu đặt ngang hàng trên cùng một trục ngang, bên trong mỗi cột xếp dọc theo Normal Flow (con số lớn ở trên, dòng chú thích ở dưới).


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: CSS Grid (repeat(5, 1fr)) hoặc Flexbox (justify-content: space-between).

Lựa chọn: Dùng display: grid; grid-template-columns: repeat(5, 1fr); gap: 16px; text-align: center; để 5 cột chia đều chiều rộng tuyệt đối, tránh lệch trục khi độ dài chữ chú thích bên dưới khác nhau. Bên trong .stat-item không cần Flex/Grid vì các phần tử xếp dọc tự nhiên theo Normal Flow.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tiêu đề "NHỮNG CON SỐ ẤN TƯỢNG"	Tiêu đề phân khu	h2
Danh sách các cặp số liệu – ý nghĩa	Dữ liệu cặp giá trị – nhãn	dl, dt, dd (hoặc ul > li)
Con số (0+, 0%...)	Giá trị thống kê	dd (hoặc strong/span)
Mô tả chỉ số	Nhãn giải thích	dt (hoặc p)
4. Phiên bản chỉ dùng div

HTML
<div class="statistics-section">
    <div class="container">
        <div class="section-title">NHỮNG CON SỐ ẤN TƯỢNG</div>
        <div class="stats-list">
            <div class="stat-item">
                <div class="stat-number">65+</div>
                <div class="stat-label">Năm truyền thống</div>
            </div>
            <!-- Lặp lại 4 cột còn lại -->
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="statistics-section">
    <div class="container">
        <h2 class="section-title">NHỮNG CON SỐ ẤN TƯỢNG</h2>
        <dl class="stats-list">
            <div class="stat-item">
                <dd class="stat-number">65+</dd>
                <dt class="stat-label">Năm hình thành và phát triển</dt>
            </div>
            <div class="stat-item">
                <dd class="stat-number">1000+</dd>
                <dt class="stat-label">Cán bộ, giảng viên</dt>
            </div>
            <div class="stat-item">
                <dd class="stat-number">95%</dd>
                <dt class="stat-label">Sinh viên có việc làm</dt>
            </div>
            <div class="stat-item">
                <dd class="stat-number">40+</dd>
                <dt class="stat-label">Ngành đào tạo</dt>
            </div>
            <div class="stat-item">
                <dd class="stat-number">100%</dd>
                <dt class="stat-label">Giảng viên đạt chuẩn</dt>
            </div>
        </dl>
    </div>
</section>
6. CSS Layout minh họa

CSS
.stats-list {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 16px;
    text-align: center;
}
7. Kết luận tư duy

Layout: stats-list → 5 stat-item (stat-number + stat-label)

CSS: CSS Grid 5 cột (repeat(5, 1fr)) + Normal Flow bên trong từng item

HTML: section → h2 + dl (div > dd + dt)

6. Section Tuyển sinh (admissions-section)
1. Nhận diện Layout Box

Plaintext
admissions-section
└── container (Flex Container chia 2 cột ngang)
    ├── admissions-media (Cột trái: khung ảnh/video)
    └── admissions-content (Cột phải: tiêu đề + mô tả + danh sách bậc học + nút xem thêm)
Giải thích: Đây là mẫu bố cục Media–Content cổ điển (50% trái là hình ảnh/media, 50% phải là nội dung giới thiệu và nút kêu gọi hành động).


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Flexbox (flex-direction: row).

Flex Container: .admissions-section .container

Flex Items: .admissions-media (flex: 1;) và .admissions-content (flex: 1;).

Thuộc tính cần thiết: display: flex; align-items: center; gap: 40px; (căn giữa theo chiều dọc để khối văn bản cân đối với khung ảnh bên trái). Bên trong .admissions-content, các phần tử xếp dọc tự nhiên theo Normal Flow.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Ảnh minh họa tuyển sinh	Hình ảnh đại diện	img
Tiêu đề "TUYỂN SINH"	Tiêu đề phân khu	h2
Đoạn giới thiệu tuyển sinh	Văn bản mô tả	p
Danh sách 3 hệ tuyển sinh	Danh mục liệt kê	ul > li > a
Nút "Xem thêm"	Liên kết chuyển trang tuyển sinh	a (tạo kiểu nút bấm)
4. Phiên bản chỉ dùng div

HTML
<div class="admissions-section">
    <div class="container">
        <div class="admissions-media">Khung ảnh tuyển sinh</div>
        <div class="admissions-content">
            <div class="section-title">TUYỂN SINH</div>
            <div class="desc">Thông tin tuyển sinh các bậc đào tạo...</div>
            <div class="program-list">
                <div class="program-item">Đại học chính quy</div>
                <div class="program-item">Sau đại học</div>
                <div class="program-item">Liên thông - Vừa làm vừa học</div>
            </div>
            <div class="btn-more">Xem thêm</div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="admissions-section">
    <div class="container">
        <div class="admissions-media">
            <img src="tuyen-sinh.jpg" alt="Hoạt động tư vấn tuyển sinh Đại học Thủy Lợi">
        </div>
        <div class="admissions-content">
            <h2>TUYỂN SINH</h2>
            <p>Thông tin tuyển sinh mới nhất dành cho thí sinh các bậc đào tạo tại Trường Đại học Thủy Lợi.</p>
            <ul>
                <li><a href="/tuyen-sinh-dai-hoc">Tuyển sinh Đại học chính quy</a></li>
                <li><a href="/tuyen-sinh-sau-dai-hoc">Tuyển sinh Sau đại học</a></li>
                <li><a href="/tuyen-sinh-khac">Hệ vừa làm vừa học & Liên thông</a></li>
            </ul>
            <a href="/tuyen-sinh" class="btn-primary">Xem thêm</a>
        </div>
    </div>
</section>
6. CSS Layout minh họa

CSS
.admissions-section .container {
    display: flex;
    align-items: center;
    gap: 40px;
}

.admissions-media,
.admissions-content {
    flex: 1;
}
7. Kết luận tư duy

Layout: container → admissions-media + admissions-content

CSS: Flexbox row (flex: 1 : flex: 1, align-items: center)

HTML: section → img + (h2, p, ul > li > a, a.btn-primary)

7. Section Đào tạo – Sinh viên – Cựu sinh viên (academic-triad-section)
1. Nhận diện Layout Box

Plaintext
academic-triad-section
└── container (Grid 3 cột bằng nhau)
    ├── pillar-card ("ĐÀO TẠO": heading + image + excerpt)
    ├── pillar-card ("SINH VIÊN": heading + image + excerpt)
    └── pillar-card ("CỰU SINH VIÊN": heading + image + excerpt)
Giải thích: Ba trụ cột đối tượng của nhà trường được đặt cạnh nhau thành 3 cột đều nhau; mỗi cột tự chứa tiêu đề riêng ở trên cùng, ảnh ở giữa và đoạn mô tả ở dưới.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: CSS Grid (grid-template-columns: repeat(3, 1fr); gap: 24px;).

Bên trong .pillar-card: Xếp dọc theo Normal Flow (h2 → img → p), không cần Flexbox.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tên từng cột ("ĐÀO TẠO", "SINH VIÊN", "CỰU SINH VIÊN")	Tiêu đề nhóm nội dung	h2
Ảnh minh họa từng nhóm	Hình ảnh đại diện	img
Đoạn giới thiệu ngắn	Mô tả nội dung	p
4. Phiên bản chỉ dùng div

HTML
<div class="academic-triad-section">
    <div class="container">
        <div class="pillar-card">
            <div class="pillar-title">ĐÀO TẠO</div>
            <div class="pillar-image">Ảnh đào tạo</div>
            <div class="pillar-desc">Mô tả chương trình đào tạo...</div>
        </div>
        <div class="pillar-card">
            <div class="pillar-title">SINH VIÊN</div>
            <div class="pillar-image">Ảnh sinh viên</div>
            <div class="pillar-desc">Mô tả đời sống sinh viên...</div>
        </div>
        <div class="pillar-card">
            <div class="pillar-title">CỰU SINH VIÊN</div>
            <div class="pillar-image">Ảnh cựu sinh viên</div>
            <div class="pillar-desc">Mô tả mạng lưới cựu sinh viên...</div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="academic-triad-section">
    <div class="container">
        <article class="pillar-card">
            <h2><a href="/dao-tao">ĐÀO TẠO</a></h2>
            <img src="dao-tao.jpg" alt="Hoạt động đào tạo">
            <p>Chương trình đào tạo đa ngành gắn liền với thực tiễn...</p>
        </article>
        <article class="pillar-card">
            <h2><a href="/sinh-vien">SINH VIÊN</a></h2>
            <img src="sinh-vien.jpg" alt="Hoạt động sinh viên">
            <p>Môi trường rèn luyện năng động, sáng tạo cho sinh viên...</p>
        </article>
        <article class="pillar-card">
            <h2><a href="/cuu-sinh-vien">CỰU SINH VIÊN</a></h2>
            <img src="cuu-sinh-vien.jpg" alt="Cựu sinh viên">
            <p>Kết nối các thế hệ cựu sinh viên Trường Đại học Thủy Lợi...</p>
        </article>
    </div>
</section>
6. CSS Layout minh họa

CSS
.academic-triad-section .container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
}
7. Kết luận tư duy

Layout: container → 3 pillar-card (h2 + img + p)

CSS: CSS Grid 3 cột (repeat(3, 1fr)) + Normal Flow

HTML: section → article (h2, a, img, p)

8. Section Các đơn vị đào tạo, khoa (faculties-section)
1. Nhận diện Layout Box

Plaintext
faculties-section (Full-bleed 50% - 50%)
├── faculty-list-panel (Nửa trái nền xanh: tiêu đề + danh sách khoa)
└── faculty-preview-panel (Nửa phải: ảnh lớn + nút liên kết nổi phía dưới)
Giải thích: Đây là khối chia đôi toàn màn hình (không bị bó trong .container 1200px ở phần nền), nửa trái chứa danh sách khoa dạng tab tương tác, nửa phải hiển thị ảnh đại diện của khoa đang được chọn kèm một nút bấm nằm đè lên cạnh dưới của ảnh.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Flexbox (2 cột ngang bằng nhau) kết hợp Position (relative / absolute) cho nút trên ảnh.

Flex Container: .faculties-section

Flex Items: .faculty-list-panel (flex: 1;) và .faculty-preview-panel (flex: 1;).

Position: .faculty-preview-panel đặt position: relative; làm mốc; .faculty-action-btn đặt position: absolute; bottom: 24px; left: 50%; transform: translateX(-50%); để căn giữa nút ở đáy ảnh.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tiêu đề "CÁC ĐƠN VỊ ĐÀO TẠO, KHOA"	Tiêu đề phân khu	h2
Danh sách tên các khoa/viện	Các nút chuyển tab	ul > li > button
Ảnh tập thể của khoa	Hình ảnh minh họa khoa	img
Nút xem chi tiết khoa	Liên kết tới trang con của khoa	a
4. Phiên bản chỉ dùng div

HTML
<div class="faculties-section">
    <div class="faculty-list-panel">
        <div class="section-title">CÁC ĐƠN VỊ ĐÀO TẠO, KHOA</div>
        <div class="faculty-tabs">
            <div class="tab-item">Khoa Công trình</div>
            <div class="tab-item active">KHOA KẾ TOÁN VÀ KINH DOANH</div>
            <div class="tab-item">Khoa Công nghệ thông tin</div>
        </div>
    </div>
    <div class="faculty-preview-panel">
        <div class="faculty-image">Ảnh tập thể khoa</div>
        <div class="faculty-action-btn">Xem chi tiết khoa</div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="faculties-section">
    <div class="faculty-list-panel">
        <h2>CÁC ĐƠN VỊ ĐÀO TẠO, KHOA</h2>
        <ul class="faculty-tabs" role="tablist">
            <li><button type="button" role="tab">Khoa Công trình</button></li>
            <li><button type="button" role="tab" aria-selected="true">KHOA KẾ TOÁN VÀ KINH DOANH</button></li>
            <li><button type="button" role="tab">Khoa Công nghệ thông tin</button></li>
        </ul>
    </div>
    <div class="faculty-preview-panel">
        <img src="khoa-ktkd.jpg" alt="Giảng viên Khoa Kế toán và Kinh doanh">
        <a href="/khoa-ke-toan-kinh-doanh" class="faculty-action-btn">Tìm hiểu thêm</a>
    </div>
</section>
6. CSS Layout minh họa

CSS
.faculties-section {
    display: flex;
    width: 100%;
}

.faculty-list-panel,
.faculty-preview-panel {
    flex: 1;
}

.faculty-preview-panel {
    position: relative;
}

.faculty-action-btn {
    position: absolute;
    bottom: 24px;
    left: 50%;
    transform: translateX(-50%);
}
7. Kết luận tư duy

Layout: faculties-section → faculty-list-panel + faculty-preview-panel (img + action-btn)

CSS: Flexbox 50/50 + position: relative/absolute

HTML: section → (h2, ul > li > button) + (img, a)

9. Mẫu chuyên mục 4 cột: Hợp tác quốc tế / Nghiên cứu / Vì cộng đồng (topic-news-section)
1. Nhận diện Layout Box

Plaintext
topic-news-section
└── container
    ├── section-title ("HỢP TÁC QUỐC TẾ" / "NGHIÊN CỨU" / "VÌ CỘNG ĐỒNG")
    └── topic-layout (Grid 4 cột bằng nhau)
        ├── topic-card (×3 cột đầu: ảnh + tiêu đề + mô tả)
        └── topic-quick-list (Cột thứ 4: danh sách 3 tin vắn dạng text)
Giải thích: Ba phân khu trên trang chủ dùng chung một mẫu kiến trúc (Reusable Pattern): 3 cột bên trái là thẻ bài viết có hình ảnh minh họa, cột thứ 4 bên phải là danh sách 3 bài viết rút gọn không ảnh xếp dọc.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: CSS Grid (grid-template-columns: repeat(4, 1fr); gap: 20px;).

Bên trong .topic-quick-list: Dùng display: flex; flex-direction: column; justify-content: space-between; gap: 16px; để 3 tin vắn dàn trải đều theo chiều cao của 3 thẻ tin bên trái.

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tiêu đề chuyên mục	Tiêu đề phân khu	h2
3 thẻ tin có ảnh	Bài viết độc lập	article (img, h3 > a, p)
Cột danh sách tin vắn bên phải	Danh sách liên kết bài viết	ul > li > a, time
4. Phiên bản chỉ dùng div

HTML
<div class="topic-news-section">
    <div class="container">
        <div class="section-title">HỢP TÁC QUỐC TẾ</div>
        <div class="topic-layout">
            <div class="topic-card">Tin có ảnh 1</div>
            <div class="topic-card">Tin có ảnh 2</div>
            <div class="topic-card">Tin có ảnh 3</div>
            <div class="topic-quick-list">
                <div class="quick-item">Tin vắn 1</div>
                <div class="quick-item">Tin vắn 2</div>
                <div class="quick-item">Tin vắn 3</div>
            </div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="topic-news-section">
    <div class="container">
        <h2 class="section-title">HỢP TÁC QUỐC TẾ</h2>
        <div class="topic-layout">
            <article class="topic-card">
                <a href="/htqt-1"><img src="htqt1.jpg" alt="Hợp tác quốc tế 1"></a>
                <h3><a href="/htqt-1">Tiêu đề tin hợp tác quốc tế 1</a></h3>
                <p>Tóm tắt nội dung hoạt động hợp tác...</p>
            </article>
            <article class="topic-card">
                <a href="/htqt-2"><img src="htqt2.jpg" alt="Hợp tác quốc tế 2"></a>
                <h3><a href="/htqt-2">Tiêu đề tin hợp tác quốc tế 2</a></h3>
                <p>Tóm tắt nội dung hoạt động hợp tác...</p>
            </article>
            <article class="topic-card">
                <a href="/htqt-3"><img src="htqt3.jpg" alt="Hợp tác quốc tế 3"></a>
                <h3><a href="/htqt-3">Tiêu đề tin hợp tác quốc tế 3</a></h3>
                <p>Tóm tắt nội dung hoạt động hợp tác...</p>
            </article>
            <ul class="topic-quick-list">
                <li><a href="/htqt-4">Tin vắn hợp tác quốc tế số 4</a></li>
                <li><a href="/htqt-5">Tin vắn hợp tác quốc tế số 5</a></li>
                <li><a href="/htqt-6">Tin vắn hợp tác quốc tế số 6</a></li>
            </ul>
        </div>
    </div>
</section>
6. CSS Layout minh họa

CSS
.topic-layout {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.topic-quick-list {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 16px;
    list-style: none;
    margin: 0;
    padding: 0;
}
7. Kết luận tư duy

Layout: topic-layout → 3 topic-card + 1 topic-quick-list

CSS: CSS Grid 4 cột (repeat(4, 1fr)) + Flex column cho cột thứ 4

HTML: section → h2 + 3 article + ul > li > a

10. Section Hình ảnh nổi bật (gallery-section)
1. Nhận diện Layout Box

Plaintext
gallery-section
└── container
    ├── section-title ("HÌNH ẢNH NỔI BẬT")
    └── bento-gallery-grid (Lưới 5 cột × 4 hàng)
        ├── gallery-item--featured (Ô trung tâm lớn: chiếm 3 cột × 2 hàng)
        └── gallery-item (14 ô ảnh nhỏ bao quanh)
Giải thích: Đây là lưới ảnh dạng Bento bất đối xứng (5 cột × 4 hàng): hàng 1 gồm 5 ô nhỏ; hàng 2 và hàng 3 có 2 ô nhỏ ở hai bên và 1 ô trung tâm khổng lồ (3 cột × 2 hàng) ở chính giữa; hàng 4 gồm 5 ô nhỏ.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: CSS Grid 2 chiều (Flexbox không thể xử lý mượt mà cấu trúc ô gộp cả hàng lẫn cột ở chính giữa như vậy).

CSS Grid:

Container: display: grid; grid-template-columns: repeat(5, 1fr); grid-auto-rows: 140px; gap: 12px;

Ô trung tâm lớn: grid-column: 2 / 5; grid-row: 2 / 4; (bắt đầu từ đường lưới cột 2 đến 5, đường lưới hàng 2 đến 4).

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Tiêu đề "HÌNH ẢNH NỔI BẬT"	Tiêu đề phân khu	h2
Mỗi khung ảnh hoạt động	Hình ảnh độc lập trong thư viện	figure > img
4. Phiên bản chỉ dùng div

HTML
<div class="gallery-section">
    <div class="container">
        <div class="section-title">HÌNH ẢNH NỔI BẬT</div>
        <div class="bento-gallery-grid">
            <div class="gallery-item">Ảnh 1</div>
            <!-- ... -->
            <div class="gallery-item gallery-item--featured">Ảnh trung tâm lớn</div>
            <!-- ... -->
            <div class="gallery-item">Ảnh 15</div>
        </div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<section class="gallery-section">
    <div class="container">
        <h2 class="section-title">HÌNH ẢNH NỔI BẬT</h2>
        <div class="bento-gallery-grid">
            <figure class="gallery-item"><img src="g1.jpg" alt="Hoạt động 1"></figure>
            <figure class="gallery-item"><img src="g2.jpg" alt="Hoạt động 2"></figure>
            <figure class="gallery-item"><img src="g3.jpg" alt="Hoạt động 3"></figure>
            <figure class="gallery-item"><img src="g4.jpg" alt="Hoạt động 4"></figure>
            <figure class="gallery-item"><img src="g5.jpg" alt="Hoạt động 5"></figure>
            <figure class="gallery-item"><img src="g6.jpg" alt="Hoạt động 6"></figure>
            <figure class="gallery-item gallery-item--featured">
                <img src="g-center.jpg" alt="Hình ảnh tiêu biểu Trường Đại học Thủy Lợi">
            </figure>
            <figure class="gallery-item"><img src="g7.jpg" alt="Hoạt động 7"></figure>
            <!-- Các ô ảnh còn lại -->
        </div>
    </div>
</section>
6. CSS Layout minh họa

CSS
.bento-gallery-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-auto-rows: 140px;
    gap: 12px;
}

.gallery-item--featured {
    grid-column: 2 / 5;
    grid-row: 2 / 4;
}

.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
7. Kết luận tư duy

Layout: bento-gallery-grid (5×4) → 1 gallery-item--featured (3×2) + 14 gallery-item (1×1)

CSS: CSS Grid 2 chiều (grid-column: 2 / 5; grid-row: 2 / 4;)

HTML: section → h2 + div (figure > img)

11. Footer (site-footer)
1. Nhận diện Layout Box

Plaintext
site-footer
└── container
    ├── footer-campuses (Tầng 1: 3 cột thông tin cơ sở/liên hệ)
    ├── footer-main (Tầng 2: 3 cột liên kết + 1 cột widget bản đồ/fanpage)
    └── footer-bottom (Tầng 3: dòng bản quyền căn giữa)
Giải thích: Footer gồm 3 tầng xếp dọc trên nền xanh đậm: tầng trên cùng liệt kê địa chỉ các phân hiệu/cơ sở; tầng giữa chia 4 cột (3 cột danh sách liên kết và 1 khung nhúng bên phải); tầng đáy chứa thông tin bản quyền.


Screenshot_25-11-2026_143641_tlu.edu.vn.jpg
2. Tư duy dàn trang CSS

Layout mode chính: Kết hợp Normal Flow (xếp 3 tầng theo chiều dọc) và CSS Grid (dàn cột bên trong tầng 1 và tầng 2).

Tầng 1 (.footer-campuses): display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px;

Tầng 2 (.footer-main): display: grid; grid-template-columns: repeat(3, 1fr) 1.4fr; gap: 24px; (cột widget thứ 4 rộng hơn nhẹ so với 3 cột link).

3. Nhận diện nội dung bên trong

Nội dung	Vai trò	HTML phù hợp
Toàn bộ chân trang	Vùng kết thúc trang	footer
Địa chỉ các cơ sở đào tạo	Thông tin liên hệ địa lý	address
Các nhóm liên kết nhanh	Danh sách link điều hướng phụ	h3 + ul > li > a
Khung bản đồ / Fanpage	Nội dung nhúng từ bên ngoài	iframe
Dòng bản quyền	Thông tin pháp lý/bản quyền	p > small
4. Phiên bản chỉ dùng div

HTML
<div class="site-footer">
    <div class="container">
        <div class="footer-campuses">
            <div class="campus-item">Cơ sở Hà Nội</div>
            <div class="campus-item">Phân hiệu Miền Nam</div>
            <div class="campus-item">Cơ sở Phố Hiến</div>
        </div>
        <div class="footer-main">
            <div class="footer-col">Nhóm liên kết 1</div>
            <div class="footer-col">Nhóm liên kết 2</div>
            <div class="footer-col">Nhóm liên kết 3</div>
            <div class="footer-widget">Khung Fanpage / Bản đồ</div>
        </div>
        <div class="footer-bottom">© Trường Đại học Thủy Lợi</div>
    </div>
</div>
5. Phiên bản HTML Semantic

HTML
<footer class="site-footer">
    <div class="container">
        <div class="footer-campuses">
            <address>175 Tây Sơn, Đống Đa, Hà Nội</address>
            <address>Số 2 Trường Sa, P.17, Q.Bình Thạnh, TP.HCM</address>
            <address>Cơ sở Phố Hiến, Hưng Yên</address>
        </div>
        <div class="footer-main">
            <div class="footer-col">
                <h3>GIỚI THIỆU</h3>
                <ul>
                    <li><a href="/tong-quan">Tổng quan</a></li>
                    <li><a href="/co-cau-to-chuc">Cơ cấu tổ chức</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h3>ĐÀO TẠO</h3>
                <ul>
                    <li><a href="/dai-hoc">Đại học</a></li>
                    <li><a href="/sau-dai-hoc">Sau đại học</a></li>
                </ul>
            </div>
            <div class="footer-col">
                <h3>LIÊN KẾT NHANH</h3>
                <ul>
                    <li><a href="/cong-sinh-vien">Cổng thông tin sinh viên</a></li>
                    <li><a href="/thu-vien">Thư viện số</a></li>
                </ul>
            </div>
            <div class="footer-widget">
                <h3>KẾT NỐI VỚI CHÚNG TÔI</h3>
                <iframe title="Bản đồ Trường Đại học Thủy Lợi" src="about:blank"></iframe>
            </div>
        </div>
        <div class="footer-bottom">
            <p><small>© 2026 Bản quyền thuộc về Trường Đại học Thủy Lợi.</small></p>
        </div>
    </div>
</footer>
6. CSS Layout minh họa

CSS
.footer-campuses {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
}

.footer-main {
    display: grid;
    grid-template-columns: repeat(3, 1fr) 1.4fr;
    gap: 24px;
}

.footer-bottom {
    text-align: center;
}
7. Kết luận tư duy

Layout: site-footer → footer-campuses (3 cột) + footer-main (4 cột) + footer-bottom

CSS: Block flow (3 tầng) + CSS Grid bên trong từng tầng

HTML: footer → address + (h3, ul > li > a, iframe) + p (small)

BƯỚC 3 — BẢN ĐỒ NHẬN DIỆN FLEXBOX TRÊN TOÀN TRANG
Plaintext
PAGE (Normal Flow dọc)
│
├── SITE-HEADER
│   ├── header-top > container             [FLEX: space-between, center]
│   │   ├── brand-box                      [NESTED FLEX: row, center]
│   │   └── header-tools                   [NESTED FLEX: row, center]
│   └── main-nav > container > nav-list    [FLEX: space-between, center]
│
├── HERO-BANNER
│   └── hero-controls                      [FLEX: column + position: absolute]
│
├── MAIN-CONTENT
│   ├── news-announcement-section          [FLEX: ratio 2 : 1]
│   │   └── news-grid                      [NESTED FLEX: ratio 1.2 : 1]
│   │       └── secondary-news-list        [NESTED FLEX: column]
│   ├── events-section > slider-pagination [FLEX: justify-content: center]
│   ├── admissions-section > container     [FLEX: ratio 1 : 1, align-items: center]
│   ├── faculties-section                  [FLEX: full-bleed 50% : 50%]
│   └── topic-quick-list                   [FLEX: column, space-between]
│
└── SITE-FOOTER                            [KHÔNG CẦN FLEXBOX — dùng Block + Grid]
Nơi KHÔNG cần Flexbox: Các khối xếp dọc đơn thuần như .admissions-content, .pillar-card, .featured-news-card (các thẻ block h2, h3, p, ul tự động xuống dòng theo Normal Flow).

BƯỚC 4 — NHẬN DIỆN & ĐÁNH GIÁ CSS GRID
Vùng giao diện	Cấu trúc hàng × cột	Tại sao chọn CSS Grid thay vì Flexbox?
event-list (Sự kiện)	1 hàng × 4 cột	Các thẻ sự kiện có chiều rộng bằng nhau tuyệt đối (repeat(4, 1fr)), không cần tính toán width: calc(25% - 15px).
stats-list (Con số ấn tượng)	1 hàng × 5 cột	Chia 5 cột đều nhau bất kể độ dài văn bản mô tả của từng chỉ số khác nhau.
academic-triad (Đào tạo – SV – CSV)	1 hàng × 3 cột	Ba cột bằng nhau với khoảng cách gap đồng nhất.
topic-layout (HTQT / Nghiên cứu / Cộng đồng)	1 hàng × 4 cột	Ép 3 thẻ tin có ảnh và 1 cột tin text có độ rộng cột bằng đúng 25% mỗi cột.
bento-gallery-grid (Hình ảnh nổi bật)	4 hàng × 5 cột (có ô gộp 3×2)	Bắt buộc dùng CSS Grid vì chỉ Grid mới điều khiển đồng thời cả trục ngang (grid-column: 2 / 5) và trục dọc (grid-row: 2 / 4) cho ô trung tâm.
footer-main (Chân trang)	1 hàng × 4 cột (1fr 1fr 1fr 1.4fr)	Dễ dàng tạo 3 cột link bằng nhau và 1 cột widget rộng hơn trên cùng một đường lưới.
BƯỚC 5 — HÀNH VI RESPONSIVE DỰ KIẾN
Thành phần	Desktop (≥ 1024px)	Tablet (768px – 1023px)	Mobile (< 768px)	Kỹ thuật CSS xử lý
main-nav	9 mục nằm ngang	Thu gọn / Menu cuộn ngang	Nút Hamburger mở Drawer	@media + ẩn .nav-list, hiện nút menu
news-announcement	Tin tức (2) | Thông báo (1)	Xếp dọc: Tin tức trên, Thông báo dưới	Xếp dọc 1 cột toàn bộ	flex-direction: column; trên container
event-list & topic-layout	A | B | C | D (4 cột)	
A | B


C | D (2 cột)

A


B


C


D (1 cột)

grid-template-columns: repeat(2, 1fr) (Tablet) → 1fr (Mobile)
stats-list	A | B | C | D | E (5 cột)	
A | B | C


D | E (3 cột)

A | B


C | D


E (2 cột)

grid-template-columns: repeat(auto-fit, minmax(150px, 1fr))
admissions & faculties	Trái (50%) | Phải (50%)	Trái (50%) | Phải (50%)	
Trên (100%)


Dưới (100%)

flex-direction: column; dưới 768px
bento-gallery-grid	Lưới 5 × 4 có ô 3×2 giữa	Lưới 3 cột đều nhau	Lưới 2 cột đều nhau	Reset grid-column: auto; grid-row: auto; trên Mobile
BƯỚC 6 — CÂY DOM GIẢ LẬP TOÀN TRANG
1. Cây DOM Semantic HTML (Chuẩn khuyến nghị)
Plaintext
body
├── header.site-header
│   ├── div.header-top > div.container
│   │   ├── a.brand-box (img + span)
│   │   └── div.header-tools (form[input, button] + a)
│   └── nav.main-nav > div.container > ul.nav-list > li > a
├── section.hero-banner
│   ├── a.hero-slide > img
│   └── div.hero-controls > button
├── main.main-content
│   ├── section.news-announcement-section > div.container
│   │   ├── div.news-column (h2 + div.news-grid[article, div > article])
│   │   └── aside.announcement-column (h2 + ul > li > a, time)
│   ├── section.events-section > div.container (h2 + div.event-list[article] + div.slider-pagination[button])
│   ├── section.statistics-section > div.container (h2 + dl.stats-list[div > dd, dt])
│   ├── section.highlight-banner-section
│   ├── section.admissions-section > div.container (div.admissions-media[img] + div.admissions-content[h2, p, ul, a])
│   ├── section.academic-triad-section > div.container > article.pillar-card (h2, img, p)
│   ├── section.faculties-section (div.faculty-list-panel[h2, ul > li > button] + div.faculty-preview-panel[img, a])
│   ├── section.topic-news-section (Hợp tác quốc tế) > div.container (h2 + div.topic-layout[article×3, ul])
│   ├── section.topic-news-section (Nghiên cứu) > div.container (h2 + div.topic-layout[article×3, ul])
│   ├── section.partners-section > div.container (h2 + p + div.partner-logos)
│   ├── section.topic-news-section (Vì cộng đồng) > div.container (h2 + div.topic-layout[article×3, ul])
│   └── section.gallery-section > div.container (h2 + div.bento-gallery-grid[figure > img])
└── footer.site-footer > div.container
    ├── div.footer-campuses > address
    ├── div.footer-main (div.footer-col[h3, ul > li > a] + div.footer-widget[h3, iframe])
    └── div.footer-bottom > p > small
2. Cây DOM chỉ dùng div (Dành cho người mới học chia hộp)
Plaintext
div.page
├── div.site-header (div.header-top + div.main-nav)
├── div.hero-banner (div.hero-slide + div.hero-controls)
├── div.main-content
│   ├── div.news-announcement-section (div.news-column + div.announcement-column)
│   ├── div.events-section (div.event-list + div.slider-pagination)
│   ├── div.statistics-section (div.stats-list > div.stat-item)
│   ├── div.highlight-banner-section
│   ├── div.admissions-section (div.admissions-media + div.admissions-content)
│   ├── div.academic-triad-section (div.pillar-card × 3)
│   ├── div.faculties-section (div.faculty-list-panel + div.faculty-preview-panel)
│   ├── div.topic-news-section × 3 (div.topic-card × 3 + div.topic-quick-list)
│   ├── div.partners-section (div.partner-logos)
│   └── div.gallery-section (div.bento-gallery-grid > div.gallery-item)
└── div.site-footer (div.footer-campuses + div.footer-main + div.footer-bottom)
BƯỚC 7 — BẢNG TỔNG HỢP TOÀN TRANG
Component	Layout Box	Layout Technique	Flex Container?	Flex Items	Nội dung chính	HTML Semantic
Header Top	.header-top .container	Flexbox	Có	.brand-box, .header-tools	Logo, tên trường, tìm kiếm	header, a, img, form, input, button
Navigation	.nav-list	Flexbox	Có	.nav-item (li)	Menu điều hướng chính	nav, ul, li, a
Hero Banner	.hero-banner	Block + Position	Không (chỉ dùng cho .hero-controls)	-	Ảnh banner & nút điều hướng	section, a, img, button
Tin tức & Thông báo	.news-announcement-section .container	Nested Flexbox	Có	.news-column (2), .announcement-column (1)	Tin nổi bật, tin phụ, thông báo	section, aside, article, h2, h3, a, time
Sự kiện	.event-list	CSS Grid (4 cột)	Không	-	4 thẻ sự kiện + dots	section, h2, article, img, h3, button
Con số ấn tượng	.stats-list	CSS Grid (5 cột)	Không	-	5 cặp số liệu thống kê	section, h2, dl, dd, dt
Tuyển sinh	.admissions-section .container	Flexbox (1 : 1)	Có	.admissions-media, .admissions-content	Ảnh, mô tả, bậc học, nút xem thêm	section, img, h2, p, ul, li, a
Đào tạo – SV – CSV	.academic-triad-section .container	CSS Grid (3 cột)	Không	-	3 trụ cột đối tượng	section, article, h2, img, p
Đơn vị đào tạo	.faculties-section	Flexbox + Position	Có	.faculty-list-panel, .faculty-preview-panel	Danh sách khoa & ảnh khoa	section, h2, ul, button, img, a
HTQT / NCKH / Cộng đồng	.topic-layout	CSS Grid (4 cột)	Không (chỉ dùng cho cột 4)	-	3 thẻ tin ảnh + 1 cột tin text	section, h2, article, ul, li, a
Hình ảnh nổi bật	.bento-gallery-grid	CSS Grid (5 × 4)	Không	-	1 ảnh trung tâm (3×2) + 14 ảnh nhỏ	section, h2, figure, img
Footer	.footer-campuses, .footer-main	Block + CSS Grid	Không	-	Địa chỉ cơ sở, 3 cột link, widget, bản quyền	footer, address, h3, ul, li, a, iframe, small
BƯỚC 8 — CÂY QUYẾT ĐỊNH DÀNH CHO SINH VIÊN
Plaintext
Nhìn thấy một vùng giao diện
        │
        ▼
Khoanh hộp (Xác định ranh giới chữ nhật bao ngoài)
        │
        ▼
Đặt tên class theo vai trò ngữ nghĩa (không đặt theo màu sắc/vị trí)
        │
        ▼
Xác định quan hệ Cha – Con
        │
        ▼
Các phần tử con bên trong cần xếp ngang hay xếp dọc?
        ├── Xếp dọc 1 chiều ──► Dùng Normal Flow mặc định (không cần Flex/Grid)
        │
        ├── Xếp ngang 1 hàng (hoặc tỷ lệ 2:1, đẩy 2 đầu) ──► Dùng Flexbox
        │
        └── Có cấu trúc lưới Hàng × Cột đều nhau hoặc gộp ô ──► Dùng CSS Grid
        │
        ▼
Có phần tử nào nằm đè lên phần tử khác không?
        ├── Có ──► Đặt position: relative ở hộp cha, position: absolute ở hộp con
        └── Không ──► Giữ nguyên dòng chảy bố cục
        │
        ▼
Nhận diện bản chất nội dung & thay thế <div> bằng thẻ HTML Semantic phù hợp
BƯỚC 9 — NGUYÊN TẮC ĐẶT TÊN CLASS
Hệ thống đặt tên class trong bài phân tích tuân theo quy tắc mô tả vai trò chức năng (Role-based Naming) và mẫu lặp nhất quán:

Tên khối phân khu (Section): [chủ-đề]-section (ví dụ: events-section, admissions-section, faculties-section).

Tên danh sách & thẻ phần tử lặp lại: [đối-tượng]-list chứa các [đối-tượng]-card hoặc [đối-tượng]-item (ví dụ: event-list > event-card, stats-list > stat-item, nav-list > nav-item).

Tránh tuyệt đối các tên class mô tả hình thức bề ngoài: Không đặt blue-box, left-column, big-image, box-1, box-2 vì khi giao diện thay đổi màu sắc hoặc chuyển sang màn hình điện thoại (cột trái trở thành khối trên), tên class sẽ bị sai lệch ý nghĩa.

BƯỚC 10 — CÁC LỖI TƯ DUY PHỔ BIẾN CẦN TRÁNH KHI DÀN TRANG
Lạm dụng Flexbox cho mọi hộp: Nhiều sinh viên đặt display: flex; flex-direction: column; cho cả những khối văn bản chỉ chứa h2, p và a. Trên thực tế, các thẻ block đã tự động xếp dọc theo Normal Flow mà không cần tốn thêm dòng CSS nào.

Dùng div thay cho mọi thẻ ngữ nghĩa ("Div-itis"): Việc bọc tiêu đề, đoạn văn, danh sách và nút bấm toàn bộ bằng div làm trình đọc màn hình (Screen Reader) và công cụ tìm kiếm (SEO) không hiểu được cấu trúc phân cấp thông tin của trang web.

Nhầm lẫn giữa thẻ <a> và thẻ <button>: Trong website tlu.edu.vn, nút "Xem thêm" ở mục Tuyển sinh dẫn người dùng sang một URL khác nên phải dùng thẻ <a>; ngược lại, các mục chọn khoa ở khối Các đơn vị đào tạo hay các chấm tròn chuyển slide chỉ làm thay đổi trạng thái hiển thị ngay tại chỗ nên phải dùng thẻ <button>.

Dùng Flexbox để ép lưới nhiều hàng nhiều cột: Khi dựng lưới 4 cột thẻ tin hoặc lưới ảnh Bento 5×4, việc dùng flex-wrap: wrap kèm width: calc(...) rất dễ gây lệch biên khi thay đổi gap hoặc gộp ô. Luôn ưu tiên CSS Grid khi bố cục có dạng ma trận hàng và cột rõ ràng.