<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Ojou-sama World</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f1220;
      color: #e6e6e6;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #7b2cff, #ff4ecd);
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
      color: #fff;
    }

    header p {
      font-size: 1.2em;
      opacity: 0.9;
      color: #fff;
    }

    nav {
      background: #111;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #ff4ecd;
    }

    section {
      padding: 80px 10%;
    }

    .section-title {
      font-size: 2.2em;
      margin-bottom: 30px;
      color: #ff4ecd;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: #1a1d33;
      padding: 25px;
      border-radius: 15px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .timeline {
      border-left: 4px solid #ff4ecd;
      padding-left: 30px;
    }

    .timeline-item {
      margin-bottom: 40px;
    }

    footer {
      background: #080a14;
      padding: 40px;
      text-align: center;
      opacity: 0.8;
    }

    footer p {
      font-size: 0.9em;
    }
    .card img {
  width: 100%;
  height: 100%;
  object-fit: cover;   /* QUAN TRỌNG */
}
table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #1f1f1f;
        }
        h4     {
  font-family: 'Inter', sans-serif;
  font-weight: 600;
  color: #ff4ecd;   /* trắng xanh nhẹ */
        }

.skill-list .tittle{
  color: #ff4ecd;           /* màu CHO SỐ + ĐỀ */
}

.skill-list .content {
  color: #E6e6e6;           /* nội dung màu khác */
  margin-top: 4px;
}
p {
  line-height: 1.5;        /* khoảng cách GIỮA CÁC DÒNG */
  margin-bottom: 16px;    /* khoảng cách GIỮA CÁC ĐOẠN */
}
.feedback {
  max-width: 900px;
  margin: 0 auto; /* căn giữa cả khối */
}

.feedback h2,
.feedback p {
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

fieldset {
  border: 1px solid #444;
  padding: 20px;
}

legend {
  padding: 0 10px;
  font-weight: bold;
}

/* TRẮC NGHIỆM – TRẢI ĐỀU */
.options {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 12px;
  margin-top: 10px;
}

.options label {
  display: flex;
  align-items: center;
  gap: 6px;
}

/* SELECT */
select {
  width: 100%;
  padding: 6px;
}

/* TỰ LUẬN – FULL NGANG */
textarea {
  width: 100%;
  resize: vertical;
  padding: 8px;
  box-sizing: border-box;
}

button {
  align-self: center;
  padding: 8px 24px;
  font-size: 16px;
}
.question {
  margin-bottom: 6px;   /* sát đáp án */
  margin-top: 24px;     /* cách câu trước */
}
.question {
  margin-top: 0;
  margin-bottom: 6px;
}
.reward {
  display: none;
  margin-top: 30px;
  text-align: center;
  animation: pop 0.6s ease-out;
}

.reward img {
  max-width: 220px;
  border-radius: 16px;
}

.reward p {
  margin-top: 8px;
  font-weight: bold;
}
.hide {
  display: none;
}

/* PHÁO HOA */
#fireworks {
  position: fixed;
  inset: 0;
  z-index: 99999;
  pointer-events: none;
}


/* HIỆU ỨNG ZENITSU POP */
@keyframes pop {
  from {
    transform: scale(0.6);
    opacity: 0;
  }
  to {
    transform: scale(1);
    opacity: 1;
  }
}
  </style>
</head>

<body>

<header>
  <h1>Zenitsu core</h1>
  <p>“	Mình đang mơ, <em>một giấc mơ hạnh phúc</em>. Mình mạnh mẽ hơn bất kỳ ai trên đời này. Mình có thể cứu giúp những người yếu thế và chứng minh rằng khoảng thời gian mà Ông huấn luyện mình không phải là vô ích.
    Một giấc mơ, nơi mà mình trở nên hữu dụng, với mọi người !!!
    
    ”</p>
</header>

<nav>
  <a href="#about">Giới thiệu</a>
  <a href="#skills">Kỹ năng</a>
  <a href="#gallery">Gallery</a>
  <a href="#timeline">Hành trình</a>

  <a href="#feedback">Khảo sát</a>
</nav>

<section id="about">
  <h2 class="section-title">Giới thiệu</h2>
  <p>
    Agatsuma Zenitsu「我妻 善逸 Agatsuma Zen'itsu」là một kiếm sĩ diệt quỷ thuộc Sát Quỷ Đội. Cậu là bạn đồng hành của Kamado Tanjirou đồng thời cũng là một trong những nhân vật chính của Kimetsu no Yaiba.
  </p>
  <h4>Thông tin cá nhân</h4>
  <table>
    <tr>
        <th>Chủng loài</th>
        <th>Sinh nhật</th>
        <th>Giới tính</th>
        <th>Tuổi</th>
        <th>Chiều cao</th>
        <th>Màu tóc</th>
        <th>Màu mắt</th>
        <th>Gia đình</th>
        <Th>Nghề nghiệp</Th>
        <Th>Tình trạng</Th>
    </tr>
    <tr>
        <td>Người</td>
        <td>3/9</td>
        <td>Nam</td>
        <td>16</td>
        <td>164,5cm</td>
        <td><p>Vàng</p>
          <p>Đen (trước đây)</p>
        </td>
        <td>Vàng kim</td>
        <td><p>Kuwajima Jogorou (Sư phụ, Đã chết)</p>
          <p>Kaigaku (Sư huynh, Đã chết)</p></td>
          <td>Kiếm sĩ diệt quỷ của sát quỷ đội</td>
          <td>Còn sống</td>
    </tr>
    
</table>
<p><h4>Ngoại hình</h4>
<p>Zenitsu là một thiếu niên có mái tóc ngắn màu vàng, với đôi mắt vàng kim cùng cặp chân mày rậm. Cậu mặt bộ đồng phục diệt quỷ tiêu chuẩn màu đen với bộ haori màu vàng có hoa văn nhiều hình tam giác nhỏ màu trắng.</p>
<h4>Tính cách</h4>
<p>Zenitsu là một người <u>nhút nhát</u>, cậu liên tục tuyên bố rằng mình không còn sống được bao lâu do công việc quá nguy hiểm là trở thành kiếm sĩ diệt quỷ. Zenitsu cũng rất <u>mê gái</u> và luôn sa vào những cô gái mà cậu cho là dễ thương, yêu cầu họ kết hôn với cậu ta nhiều đến mức khiến người khác khó chịu.</p>
<p>Zenitsu rất tôn trọng và ngưỡng mộ đồng đội, đặc biệt là với người thầy quá cố của mình, Shihan. Khi Zenitsu trở nên <u>nghiêm túc và tập trung</u>, cậu hầu như dẹp bỏ phần nhút nhát của con người mình và chiến đấu với một nhân cách hoàn toàn khác.</p>
</section>

<section id="skills">
  <h2 class="section-title">Kỹ năng</h2>
  <div class="grid">
    <div class="card">
      <h3>Khả năng tự nhiên</h3>
      Thính giác nhạy bén, Chiến đấu vô thức, Tốc độ cực cao.
    </div>
    <div class="card">
      <h3>Kiếm Thuật</h3>
      Lục Liên, Bát Liên, Thần Tốc, Hỏa Lôi Thần.
    </div>
    
  </div>
  <ol class="skill-list">
    <li><p><h4>Khả năng tự nhiên:</h4></li>
    <ul>
      <li><p><u>Thính giác nhạy bén</u>: Zenitsu có một thính giác nhạy bén, cho cậu khả năng <strong>phát hiện nguy hiểm</strong> từ âm thanh, kể cả những âm thanh nhỏ nhất. Thính giác của Zenitsu tốt đến độ cậu vẫn có thể nghe được người khác <strong>khi đang ngủ</strong>, cậu có thể nghe âm thanh từ <strong>mạch máu, nhịp tim</strong> và dễ dàng phân biệt được thứ âm thanh của người lẫn quỷ. Cậu cũng có thể nghe được <strong>tiếng lòng, cảm xúc</strong> của người khác nhờ thính giác của mình.</p></li>
      <li><p><u>Chiến đấu vô thức</u>: Zenitsu có thể chiến đấu ngay cả <strong>khi đang ngủ</strong>. Mỗi khi gặp nguy hiểm, nỗi sợ hãi của cậu vượt quá giới hạn của bản thân khiến cậu bất tỉnh. Trong lúc ngủ, Zenitsu có thể sử dụng kiếm thuật của mình hoàn toàn chỉ dựa vào bản năng. Tuy nhiên, khi dần trải qua nhiều khó khăn và nguy hiểm, Zenitsu ngày càng cải thiện cả kỹ năng và lòng can đảm theo thời gian, vì vậy cậu ngày càng ít phụ thuộc vào khả năng này.</p></li>
      <li><p><u>Tốc độ cực cao</u>: Zenitsu là một trong những kiếm sĩ <strong>nhanh nhất</strong> của Sát Quỷ Đội, cậu sở hữu một tốc độ di chuyển cực cao và phản xạ cực linh hoạt. Như khi cậu rút kiếm cắt đứt lưỡi một con quỷ cực kì nhanh gọn và chính xác. Đặc biệt khi đang dùng <strong>Hỏa Lôi Thần</strong>, tốc độ của cậu được mô tả là hoàn toàn nằm ngoài sự nhận thức.</p></li>
  </ul>

    <li><h4>Kiếm Thuật:</h4></li>
    <ul>
    <li><p><u>Phích Lịch Nhất Thiểm・Lục Liên</u>: Zenitsu tung ra Phích Lịch Nhất Thiểm <strong>sáu lần liên tiếp</strong>, giúp gia tăng thêm rất nhiều tốc độ và tiếp cận kẻ địch một cách nhanh chóng, đòn này thậm chí làm <strong>rung chuyển cả không gian</strong> và tạo ra <strong>tiếng sét đánh</strong> cực lớn.</p></li>
    <li><p><u>Phích Lịch Nhất Thiểm・Bát Liên</u>: <strong>Nâng cấp</strong> từ Lục Liên, Zenitsu tung ra Phích Lịch Nhất thiểm <strong>tám lần liên tiếp</strong>.</p></li>
    <li><p><u>Phích Lịch Nhất Thiểm・Thần Tốc</u>: Zenitsu có thể sử dụng kỹ thuật này để <strong>gia tăng thêm tốc độ</strong> cho Phích Lịch Nhất Thiểm. Khiến cậu di chuyển với một tốc độ cực kì nhanh đồng thời <strong>gia tăng lực chém</strong> của bản thân lên đáng kể.</p></li>
    <li><p><u>Hỏa Lôi Thần</u>: Là thức kiếm do Zenitsu <strong>sáng tạo</strong> ra. Khi sử dụng cơ thể cậu trở nên <strong>phát sáng</strong> với hào quang của một con rồng lửa và sấm sét, cho cậu khả năng di chuyển với một <strong>tốc độ cực kì khủng khiếp</strong>, có thể lao đến chém bay đầu tân Thượng Huyền Lục Kaigaku trước khi hắn nhận thức được điều gì đang xảy ra. Zenitsu thừa nhận rằng cậu tự sáng tạo ra thức kiếm này với mục đích muốn chiến đấu bên cạnh Kaigaku.</p></li>
  </ul>
</ol>
</section>

<section id="gallery">
  <h2 class="section-title">Gallery</h2>
  <audio src="bandicam-2025-12-30-13-30-39-162.mp3" controls></audio>
    <p>Đoạn âm thanh gắn liền với các phân cảnh chiến đấu của nhân vật Zenitsu Agatsuma trong Kimetsu no Yaiba.</p>

  <div class="grid">
    <div class="card">
      <img src="dd0f562d59a6f3521b643e5113e69224.jpg" >
    </div>
    <div class="card">
      <img src="41aa1675e73340f7304cab7413c62847.jpg" >
    </div>
    <div class="card">
      <img src="322a8676d4cbf0794be7de0d97a3f837.jpg" >
    </div>
      </div>

</section>

<section id="timeline">
  <h2 class="section-title">Hành trình</h2>
  <div class="timeline">
    <div class="timeline-item">
      <h3>Giai đoạn 1</h3>
      <p>Khi Zenitsu còn là một đứa trẻ, cậu bị một người phụ nữ lừa gạt và buộc phải gánh một khoản nợ cực kì lớn. Trong lúc khủng hoảng, cậu đã gặp được Ông Kuwajima Jigorou (cựu Minh Trụ), người đã cứu giúp cậu khỏi quãng thời gian khó khăn.</p>
    </div>
    <div class="timeline-item">
      <h3>Giai đoạn 2</h3>
      <p>Ông quyết định sẽ huấn luyện Zenitsu thành kiếm sĩ diệt quỷ cùng với đại đệ tử của mình, Kaigaku. Trong một ngày luyện tập mệt nhử, Zenitsu đã trốn trên một cái cây vì cảm thấy mình đã làm Ông thất vọng, đột nhiên một tia sét đánh trúng cậu, khiến tóc và lông mày của cậu chuyển thành màu vàng.</p>
    </div>
    <div class="timeline-item">
      <h3>Giai đoạn 3</h3>
      <p>Zenitsu và Kaigaku rất ghét nhau, tuy nhiên Zenitsu vẫn tôn trọng Kaigaku với tư cách như một huynh đệ đồng môn. Với mong muốn chiến đấu bên cạnh Kaigaku, cậu đã tự sáng tạo ra một thức mới của Hơi Thở của Sấm Sét, có tên "Hỏa Lôi Thần". </p>
    </div>
  </div>
</section>
<section id="feedback">
  <h2 class="section-title">Khảo sát</h2>
  <p>
    Phần biểu mẫu dưới đây nhằm ghi nhận cảm nhận của người xem sau khi
    tìm hiểu về nhân vật Zenitsu Agatsuma và trải nghiệm các nội dung minh họa.
  </p>

  <form id="feedbackForm" onsubmit="submitForm(event)">
    <!-- Trắc nghiệm -->
    <fieldset>
      

      <p class ="question">1. Bạn ấn tượng với đặc điểm nào của Zenitsu?</p>
      <label>
        <input type="checkbox" name="impress" value="tinh-cach">
        Tính cách nhút nhát nhưng bộc phát mạnh mẽ
      </label><br>
      <label>
        <input type="checkbox" name="impress" value="suc-manh">
        Sức mạnh khi rơi vào trạng thái ngủ
      </label><br>
      <label>
        <input type="checkbox" name="impress" value="cam-xuc">
        Ngoại hình đặc biệt
      </label><br>
      <label>
        <input type="checkbox" name="impress" value="khac">
        Yếu tố khác
      </label>
<p></p>
      <p class ="question">2. Mức độ yêu thích của bạn đối với nhân vật Zenitsu là:</p>
      <div class="option">
      <label>
        <input type="radio" name="feeling" value="cam-dong">
        Chân ái
      </label><br>
      <label>
        <input type="radio" name="feeling" value="bat-ngo">
        Rất mê
      </label><br>
      <label>
        <input type="radio" name="feeling" value="giai-tri">
        Khá thích
      </label><br>
      <label>
        <input type="radio" name="feeling" value="binh-thuong">
        Bình thường
      </label><br>
      <label>
        <input type="radio" name="feeling" value="binh-thuong">
        Không hợp gu
      </label></div>
      <p></p>
      <p>3. Theo bạn, mức đánh giá phù hợp nhất cho chất lượng tổng thể của trang web này là:
      <select name="voice">
        <option value="">-- Chọn một đáp án --</option>
        <option value="rat-phu-hop">10 điểm</option>
        <option value="phu-hop">Điểm tối đa</option>
        
      </select>
    <p></p>

    <!-- Tự luận -->
    

      
      <p>4. Nếu mô tả Zenitsu bằng một từ, bạn sẽ chọn từ gì? 
      <textarea name="one-word" rows="3" placeholder="Nhập ý kiến của bạn..."></textarea>
    </fieldset>
    
    <button type="submit">Gửi phản hồi</button>
  </form>
  <div id="reward" class="reward">
    <img src="9621832c01c2fcfe8dffdedd7df6781e.jpg" alt="Zenitsu cười">
    <p>Cảm ơn bạn đã phản hồi! ⚡</p>
  </div>
</section>
<section id="contact">
  <h2 class="section-title">Liên hệ</h2>
  <p><a href="https://animevietsub.show/phim/thanh-guom-diet-quy-kimetsu-no-yaiba-i7-a3445/">Xem phim đi</a></p>
  
</section>

<footer>
  <p>© Agatsuma Zenitsu | Built by Ojou-sama</p>
</footer>
<script>
 function submitForm(e) {
  e.preventDefault();

  const form = document.getElementById("feedbackForm");
  const reward = document.getElementById("reward");
  const section = document.getElementById("feedbackSection");

  // 1. Ẩn form
  form.style.display = "none";

  // 2. Hiện Zenitsu
  reward.style.display = "block";

  // 3. Cuộn lên đầu section để KHÔNG bị khuất
  section.scrollIntoView({ behavior: "smooth", block: "start" });

  // 4. Bắn pháo hoa
  launchFireworks();
}

/* PHÁO HOA ĐẢM BẢO THẤY */
function launchFireworks() {
  const canvas = document.getElementById("fireworks");
  const ctx = canvas.getContext("2d");

  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;

  let particles = [];

  for (let i = 0; i < 120; i++) {
    particles.push({
      x: Math.random() * canvas.width,
      y: canvas.height,
      vx: (Math.random() - 0.5) * 6,
      vy: -Math.random() * 8 - 4,
      life: 80,
      size: Math.random() * 3 + 1
    });
  }

  function animate() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);

    particles.forEach((p, i) => {
      p.x += p.vx;
      p.y += p.vy;
      p.life--;

      ctx.beginPath();
      ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
      ctx.fillStyle = "gold";
      ctx.fill();

      if (p.life <= 0) particles.splice(i, 1);
    });

    if (particles.length > 0) {
      requestAnimationFrame(animate);
    }
  }

  animate();
}
</script>
</body>
</html>
