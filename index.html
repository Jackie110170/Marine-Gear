<?php
// 獲取語言選擇，默認為中文
$lang = isset($_GET['lang']) ? $_GET['lang'] : 'en';
include "lang/$lang.php";
?>
<!DOCTYPE html>
<html lang="<?= $lang ?>">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?= $content['title'] ?></title>
	  <!-- Main CSS File -->
    <link rel="stylesheet" href="style.css">
	
	  <!-- Vendor CSS Files -->
	<link href="bootstrap.min.css" rel="stylesheet">
 	<link href="bootstrap-icons.css" rel="stylesheet">
    <link href="aos.css" rel="stylesheet"> 
  	<link href="glightbox.min.css" rel="stylesheet">
  	<link href="swiper-bundle.min.css" rel="stylesheet">


	<!-- Swiper CSS -->
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">
	 <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
	
	
	<!-- Main JS File -->
    <script src="scripts/main.js"></script>

	 <!-- Preloader -->
 
<!-- Vendor JS Files -->
<script src="scripts/bootstrap.bundle.min.js"></script>
<script src="/scripts/validate.js"></script>
<script src="/static/assets/vendor/aos/aos.js"></script>
<script src="/scripts/glightbox.min.js"></script>
<script src="/scripts/noframework.waypoints.js"></script>
<script src="/scripts/purecounter_vanilla.js"></script>
<script src="/scripts/swiper-bundle.min.js"></script>
<script src="/scripts/imagesloaded.pkgd.min.js"></script>
<script src="/scripts/isotope.pkgd.min.js"></script>
<script src="scripts/aos.js"></script>
		
</head>
	
	<script>
  //產品預設篩選
document.addEventListener("DOMContentLoaded", function() {
    // 初始化 Isotope
    var iso = new Isotope('.isotope-container', {
        itemSelector: '.portfolio-item',
        layoutMode: 'masonry',
        filter: '*' // 預設顯示所有項目
    });

    // 取得導航欄中與 portfolio 篩選相關的篩選按鈕
    const navFilterLinks = document.querySelectorAll('.dropdown a[href="#portfolio"][data-filter]');
    const filterItems = document.querySelectorAll('.portfolio-filters li');

    // 為每個導航欄的篩選按鈕添加點擊事件
    navFilterLinks.forEach(link => {
        link.addEventListener('click', function(event) {
            event.preventDefault();

            // 取得篩選條件
            const filterValue = this.getAttribute('data-filter');

            // 使用 Isotope 應用篩選
            iso.arrange({ filter: filterValue });

            // 滾動到 portfolio 區域
            document.querySelector('#portfolio').scrollIntoView({
                behavior: 'smooth'
            });

            // 移除篩選器中的所有按鈕的 active 樣式
            filterItems.forEach(item => {
                item.classList.remove('filter-active');
            });

            // 尋找並更新篩選器中的相應按鈕
            const correspondingFilterItem = document.querySelector(`.portfolio-filters li[data-filter="${filterValue}"]`);
            if (correspondingFilterItem) {
                correspondingFilterItem.classList.add('filter-active');
            }
        });
    });

    // 為每個篩選器中的篩選按鈕添加點擊事件
    filterItems.forEach(item => {
        item.addEventListener('click', function(event) {
            event.preventDefault();

            // 取得篩選條件
            const filterValue = this.getAttribute('data-filter');

            // 使用 Isotope 應用篩選
            iso.arrange({ filter: filterValue });

            // 移除所有篩選按鈕的 active 樣式
            filterItems.forEach(li => {
                li.classList.remove('filter-active');
            });

            // 為當前點擊的按鈕添加 active 樣式
            this.classList.add('filter-active');
        });
    });
});

</script>

	
<body class="index-page">
    <header id="header" class="header sticky-top">
           <div class="container position-relative d-flex align-items-center justify-content-between">
        <a  class="logo d-flex align-items-center">
        <img src="images/logo.png" alt="Logo"> <!-- 根據實際需求調整高度 -->
     </a>
    </div>
  
               <nav id="navmenu" class="navmenu">
            <ul>
                <li><a href="#about"><?= $content['nav_about'] ?></a></li>
                <li><a href="#services"><?= $content['nav_services'] ?></a></li>
                <li><a href="#gallery"><?= $content['nav_gallery'] ?></a></li>
                <li><a href="#contact"><?= $content['nav_contact'] ?></a></li>
				 <i class="bi bi-globe"></i> <!-- 這裡是地球圖標 -->
                <li>
                    <a href="?lang=zh" <?= $lang === 'zh' ? 'class="active"' : '' ?>>中文</a></li>
                  <li>  <a href="?lang=en" <?= $lang === 'en' ? 'class="active"' : '' ?>>English</a>
                </li>
            </ul>
        </nav>
    </header>
	
	<main>
    
	<style>
  .filter-active {
    font-weight: bold;
    color: #ff5733; /* 高亮顏色 */
}
@media only screen and (max-width: 600px) {
  .form-container {
    display: none !important; /* 強制隱藏該區塊 */
  }
 
}

.scroll-top {
  background-color: #e04f30; /* 底部顏色 */
  border-radius: 50%; /* 圓形效果 */
  width: 40px; /* 你可以根據需要調整這裡的大小 */
  height: 40px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.scroll-top i {
  color: #ffffff; /* 鈴鐺圖標顏色 */
  font-size: 24px; /* 圖標大小 */
}

.scroll-top:hover {
  background-color: #c03b25; /* 懸停時的底色變化，可以根據需要修改 */
}

</style>
	<script>
  /*圓餅圖*/
document.addEventListener("DOMContentLoaded", function () {
  const circles = document.querySelectorAll(".progress-circle");

  circles.forEach((circle) => {
    const percent = circle.getAttribute("data-percent");
    const fullMask = circle.querySelector(".mask.full .fill");
    const halfMask = circle.querySelector(".mask.half .fill");

    // 設定旋轉角度
    if (percent <= 50) {
      fullMask.style.transform = `rotate(${(percent / 50) * 180}deg)`;
    } else {
      fullMask.style.transform = "rotate(180deg)";
      halfMask.style.transform = `rotate(${((percent - 50) / 50) * 180}deg)`;
    }
  });
});

/*進度條*/

document.addEventListener("DOMContentLoaded", function () {
    const progressBars = document.querySelectorAll('.progress-bar');

    progressBars.forEach(function (progressBar) {
        const targetWidth = parseInt(progressBar.getAttribute('data-width'), 10); // 目標寬度百分比
        const skillElement = progressBar.closest('.progress').querySelector('.val'); // 找到顯示百分比的元素
        let currentWidth = 0;
        const duration = 500; // 動畫總持續時間（以毫秒為單位）
        const fps = 60; // 每秒幀數（60次更新）
        const interval = duration / fps; // 每次更新之間的時間間隔
        const step = targetWidth / fps; // 每幀應增加的百分比

        // 動畫更新
        const animateProgress = setInterval(function () {
            if (currentWidth < targetWidth) {
                currentWidth += step;
                progressBar.style.width = `${Math.round(currentWidth)}%`; // 更新進度條寬度
                skillElement.textContent = `${Math.round(currentWidth)}%`; // 同步更新百分比數字
            } else {
                clearInterval(animateProgress); // 動畫完成後停止
                progressBar.style.width = `${targetWidth}%`; // 確保最終寬度正確
                skillElement.textContent = `${targetWidth}%`; // 確保最終百分比正確
            }
        }, interval);
    });
});

</script>
		
    <main class="main">
		
  		<section class="hero section light-background" id="hero">
			<div class="container-fluid">
			<div class="row gy-4">
			<div class="col-lg-6 offset-lg-1 order-2 order-lg-1 d-flex flex-column justify-content-center" > 
			<div data-aos="zoom-out">
				<script>AOS.init(); </script>
			<h1 class="no-wrap"><?= $content['welcome'] ?><span style="color: #e74c3c;"> </span><span style="color: #E04F30 ;">Marine Gear</span></h1>

			<p><?= $content['slogan'] ?></p>

		<div class="d-flex"><a class="btn-get-started" href="#about" style="background-color: #E04F30; color: #ffffff;"><p><?= $content['started'] ?></p> </a>  </div>
</div>
</div>
</div>
</div>
</section>
	
		
		
		<!-- Swiper Container -->
	<section id="clients" style="padding: 20px 0;">
    <div style="max-width: 100%; margin: 0 auto;">
	
    <div class="swiper" style="position: relative; overflow: hidden;">
		 
        <div class="swiper-wrapper">
			
            <div class="swiper-slide"><img src="images/1.jpg" alt="Client 1" style="width: 400px; height: 300px; object-fit: cover;"></div>
            <div class="swiper-slide"><img src="images/2.jpg" alt="Client 2" style="width: 400px; height: 300px; object-fit: cover;"></div>
            <div class="swiper-slide"><img src="images/3.jpg" alt="Client 3" style="width: 400px; height: 300px; object-fit: cover;"></div>
            <div class="swiper-slide"><img src="images/4.jpg" alt="Client 4" style="width: 400px; height: 300px; object-fit: cover;"></div>
            <div class="swiper-slide"><img src="images/5.jpg" alt="Client 5" style="width: 400px; height: 300px; object-fit: cover;"></div>
        </div>
		
		<!-- Navigation buttons -->
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
  
        <!-- Pagination -->
        <div class="swiper-pagination"></div>
	    
    </div>
		</div>
	</section>	
		
	<script>
    document.addEventListener('DOMContentLoaded', function () {
      var mySwiper = new Swiper('.swiper', {
        loop: true,
        speed: 1000,
        autoplay: {
          delay: 3000,
          disableOnInteraction: false
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev'
        },
        pagination: {
          el: '.swiper-pagination',
          type: 'bullets',
          clickable: true
        },
        slidesPerView: 3,  // 一次顯示3張圖片
        spaceBetween: 30,  // 每張圖片之間的間距
        breakpoints: {
          320: {
            slidesPerView: 1,
            spaceBetween: 10
          },
          640: {
            slidesPerView: 2,
            spaceBetween: 20
          },
          768: {
            slidesPerView: 3,
            spaceBetween: 30
          },
          1024: {
            slidesPerView: 4,
            spaceBetween: 40
          }
        }
      });
    });
  </script>

		
	<section id="about" class="featured-services section">
 
  
    <div class="container section-title" data-aos="fade-up">
      
      <h2><span style="color: #ecf0f1;"><?= $content['about_title'] ?></span></h2>
		
		<p><span class="description-title"><span style="color: #E04F30 ;"><?= $content['company_name'] ?></span><span style="color: #000000;"><?= $content['story'] ?></span></span></p>
      
    </div> 

    <div class="container">

      <div class="row gy-3">

        <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
			
		<?php
	// 檢查 GET 參數 lang 的值
	$lang = isset($_GET['lang']) ? $_GET['lang'] : 'default';

	  if ($lang === 'en') {
    $imagePath = 'images/slogan_en.png';
	  } elseif ($lang === 'zh') {
    $imagePath = 'images/slogan_CH.png';
	  } else {
    $imagePath = 'images/slogan_en.png'; // 預設圖像
	  }
				
		
	  // 在頁面中輸出對應的圖像
	  echo '<img src="' . $imagePath . '" alt=""  class="align-left img-fluid" >';
			?>
	</div> 

		   

			
	    <div class="col-lg-6 d-flex flex-column justify-content-center" data-aos="fade-up" data-aos-delay="200">
	<div class="about-content ps-0 ps-lg-3 custom-panel">
	<h3 style="text-align: center;"> </h3>

	<h3 style="text-align: center;"><strong><span style="color: #E04F30 ;"><?= $content['company_name2'] ?></span></strong></h3>

	<hr>
	<p style="text-align: center;"><?= $content['about_text1'] ?></p>

	<p style="text-align: center;"><?= $content['about_text2'] ?></p>

	<p style="text-align: center;"><?= $content['about_text3'] ?></p>

<!--<p style="text-align: center;">無論客戶對於濾網的尺寸、效率及規格需求</p>

<p style="text-align: center;">我們將給予最棒的解決方案</p> -->
	</div>
 

<ul class="spaced-list">
	<li style="text-align: center;"> <h4><span><?= $content['services_list14'] ?> </span></h4></li>
	<li style="text-align: center;"><?= $content['services_list15'] ?></li>
	<li style="text-align: center;"><h4><span><?= $content['services_list16'] ?></span></h4></li>
	<li style="text-align: center;"> </li>
	<li style="text-align: center;"><?= $content['services_list17'] ?></li>
	<li style="text-align: center;"><h4><span><?= $content['services_list18'] ?></span></h4></li>
	<li style="text-align: center;"> </li>
	<li style="text-align: center;"><?= $content['services_list19'] ?></li>
	<li style="text-align: center;"><h4><span><?= $content['services_list20'] ?></span></h4></li>
	<li style="text-align: center;"><?= $content['services_list21'] ?></li>
	<li style="text-align: center;"> </li>
	
</ul>
</div>
        
         
      </div>

    </div>
    
  </section>
			
<section id="core_value" class="about section">
      <div class="container section-title" data-aos="fade-up">
        
        <h2><span style="color: #ecf0f1;"><?= $content['services_title3'] ?></span></h2>

<p><span class="description-title"><span style="color: #E04F30 ;"><?= $content['services_title4'] ?></span></span><span style="color: #000000;"><?= $content['services_title5'] ?></span></p>
        
      </div><!-- End Section Title -->
    
      <div class="container">
        <div class="row gy-3 align-items-center" style="margin-left: -15px; margin-right: -15px;"> <!-- 減少左右的外邊距 -->
          
          <!-- 左邊內容，寬度9欄 -->
            
            <div class="col-lg-7 d-flex flex-column justify-content-center" data-aos="fade-up" data-aos-delay="100">
<div class="about-content ps-0 ps-lg-4 custom-panel">
<h3><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list2'] ?></font></font></strong></h3>

<p class="centered-text"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list3'] ?></font></font>
	<!--<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推動公司持續發展</font></font></p> -->
</div>

<ul class="spaced-list">
	<li style="text-align: center;"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list4'] ?></font></font></strong></li>
	<li style="text-align: center;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list5'] ?> </font></font></li>
	
	<li style="text-align: center;"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list6'] ?></font></font></strong></li>
	<li style="text-align: center;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list7'] ?></font></font></li>
	
	<li style="text-align: center;"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list8'] ?></font></font></strong></li>
	<li style="text-align: center;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list9'] ?></font></font></li>
	
	<li style="text-align: center;"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list10'] ?></font></font></strong></li>
	<li style="text-align: center;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list11'] ?></font></font></li>
	
	<li style="text-align: center;"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list12'] ?></font></font></strong></li>
	<li style="text-align: center;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"><?= $content['services_list13'] ?></font></font></li>

</ul>
</div>

<div class="col-lg-5 text-center" data-aos="fade-up" data-aos-delay="100">

<img src="images/output.png"    alt=""     width="400"     height="400"    class="img-fluid">
	
		<?php
	// 檢查 GET 參數 lang 的值
	$lang = isset($_GET['lang']) ? $_GET['lang'] : 'default';

	  if ($lang === 'en') {
    $imagePath = 'images/slogan_en2.png';
	  } elseif ($lang === 'zh') {
    $imagePath = 'images/slogan_CH2.png';
	  } else {
    $imagePath = 'images/slogan_en2.png'; // 預設圖像
	  }
				
	  // 在頁面中輸出對應的圖像
	  echo '<img src="' . $imagePath . '" alt=""  width="400" height="400"  class="img-fluid" >';
			?>
	</div> 
    
        </div>
      </div>
    </section>		
			
			
			
		<!-- Portfolio Section -->
<section id="gallery" class="portfolio section">
<style>
    @media (max-width: 575px) {
        /* 手機模式: 一行兩個 */
        .portfolio-item {
            flex: 0 0 50%; /* 設定每個產品佔 50% 的寬度，達到一行兩個的效果 */
            max-width: 50%;
            padding: 5px; /* 控制每個產品之間的間距 */
        }

        .portfolio-item img {
            width: 100%; /* 使圖片自適應容器寬度 */
            height: auto; /* 使圖片等比例縮放 */
        }
    }
</style>
	
    <!-- Section Title -->
    <div class="container section-title" data-aos="fade-up">
        
        <h2><span style="color: #ecf0f1;"><?= $content['gallery_title'] ?></span></h2>

<p><span><?= $content['gallery_title2'] ?></span><span class="description-title"><span style="color: #E04F30 ;"><?= $content['gallery_title3'] ?></span></span></p>
		
        
    </div><!-- End Section Title -->	
	<div class="container">
		<div class="row gy-4 isotope-container" data-aos="fade-up" data-aos-delay="200">
                
                <div class="col-lg-3 col-md-6 col-sm-6 col-6 portfolio-item isotope-item ">
                    <a >
                        <img src="images/0505.png" class="img-fluid" alt="">
                    </a>
		</div>
		 <div class="col-lg-3 col-md-6 col-sm-6 col-6 portfolio-item isotope-item ">
                    <a >
                        <img src="images/1905.png" class="img-fluid" alt="">
                    </a>
		</div>
		<div class="col-lg-3 col-md-6 col-sm-6 col-6 portfolio-item isotope-item ">
                    <a >
                        <img src="images/6160.png" class="img-fluid" alt="">
                    </a>
		</div>
			<div class="col-lg-3 col-md-6 col-sm-6 col-6 portfolio-item isotope-item ">
                    <a >
                        <img src="images/9390.png" class="img-fluid" alt="">
                    </a>
		</div>
	</div>
	
	
	
	<section id="services" class="service section">
    <!-- Section Title -->
    
    <div class="container section-title" data-aos="fade-up">
<h2><span style="color: #ecf0f1;"><?= $content['services_title'] ?></span></h2>

<p><span class="description-title"><span style="color: #E04F30 ;"><?= $content['company_name'] ?></span><span style="color: #000000;"><?= $content['services_title2'] ?></span></span></p>
</div>
    

    <div class="container">
      <div class="row gy-4">
                
        <!-- Service Item 1 -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="100">
          <div class="service-item position-relative">
            <div class="icon icon-large"> <!-- 使用 icon-large 來放大這個圖標 -->
              <i class="bi bi-bounding-box-circles"></i>
            </div>
            
            <p> </p>

<h3><?= $content['services_list22'] ?></h3>

<p> </p>

<p><?= $content['services_list23'] ?></p>



<p> </p>
            
          </div>
        </div><!-- End Service Item 1 -->

        <!-- Service Item 2 -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="200">
          <div class="service-item position-relative">
            <div class="icon icon-large"> <!-- 使用 icon-large 來放大這個圖標 -->
              <i class="bi bi-calendar4-week"></i>
            </div>
            
            <p> </p>

<h3><?= $content['services_list24'] ?></h3>

<p> </p>

<p><?= $content['services_list25'] ?></p>

<p> </p>
            
          </div>
        </div><!-- End Service Item 2 -->

		  <!-- Service Item 4 -->
        <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="300">
          <div class="service-item position-relative">
            <div class="icon icon-large"> <!-- 使用 icon-large 來放大這個圖標 -->
            <i class="bi bi-menu-button-wide"></i>
            </div>
            
            <p> </p>

<h3><?= $content['services_list26'] ?></h3>

<p> </p>

<p><?= $content['services_list27'] ?></p>


<p> </p>
            
          </div>
        </div><!-- End Service Item 4 -->
		  
		  
		  
        <!-- Service Item 3 -->
<!--    <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="400">
          <div class="service-item position-relative">
            <div class="icon icon-large"> <!-- 使用 icon-large 來放大這個圖標 -->
				
<!--               <i class="bi bi-chat-square-text"></i>
            </div>
            
            <p> </p>

<h3>專業諮詢</h3>

<p> </p>

<p>服務範圍涵蓋國內外眾多客戶群</p>

<p>憑藉豐富技術知識與高品質的產品</p>

<p>針對客戶的各種過濾需求</p>

<p>提供專業且深入的解決方案</p>

<p> </p>
            
          </div> 
        </div>
-->
<!-- End Service Item 3 -->

      </div> <!-- End Row -->
    </div> <!-- End Container -->

</section><!-- /Service Section -->

   
	 <!-- Portfolio Section -->
    <section id="contentus" class="contentus section">

      
      <!-- Contact Section -->

<section id="contact" class="contact section">

    <!-- Section Title -->
    <div class="container section-title" data-aos="fade-up">
    
    <h2><span style="color: #ecf0f1;"><?= $content['contact_title'] ?></span></h2>

<p><span><?= $content['contact_title2'] ?></span> <span class="description-title"><span style="color: #E04F30 ;"><?= $content['contact_title3'] ?></span></span></p>
    
 
    </div><!-- End Section Title -->
 
    <div class="container" data-aos="fade-up" data-aos-delay="100">

      <div class="row gy-4">

        <div class="col-lg-5">
          <div class="info-wrap">
              <!-- 分頁導航 
              <ul class="nav nav-tabs" id="locationTabs" role="tablist" >
                  <li class="nav-item">
                      <a class="nav-link active"  style="color: #e04f30;" id="taiwan-tab" data-bs-toggle="tab" href="#taiwan" role="tab" aria-controls="taiwan" aria-selected="true"><p>台灣</p></a>
                  </li>
                  <li class="nav-item">
                      <a class="nav-link" style="color: #e04f30;" id="philippines-tab" data-bs-toggle="tab" href="#philippines" role="tab" aria-controls="philippines" aria-selected="false"><p>菲律賓</p></a>
                  </li>
              </ul>-->
      
              <!-- 分頁內容 -->
              <div class="tab-content" id="locationTabsContent">
                  <!-- 台灣內容 -->
                  <div class="tab-pane fade show active" id="taiwan" role="tabpanel" aria-labelledby="taiwan-tab">
                      <!-- 台灣的 CMS 內容 -->
                      
                      <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
<div>
<h3> </h3>
<h3><?= $content['contact_info2'] ?></h3>
<p>No. 100 Geronimo Street, Buenmar Subd. C. Raymundo Avenue, Maybunga, Pasig, 1607 Metro Manila </p>
</div>
</div>
<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="300">
<div>
<h3><?= $content['contact_info1'] ?></h3>
<p>(02)8643-5693</p>
</div>
</div>
<!--<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="400">
<div>
<h3>FAX</h3>
<p>+886-3-3414782</p>
</div>
</div>-->
<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="500">
<div>
<h3>Email</h3>
<p>Jackie110170@163.com</p>
</div>
</div>
                      
                      <!-- 菲律賓map -->
                      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3861.406530023512!2d121.08214489815191!3d14.575896124122117!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3397c7e0b1138725%3A0x26974e91bb4044ed!2sTsung%20Fang%20Industrial%20Corporation!5e0!3m2!1szh-TW!2sph!4v1732419267688!5m2!1szh-TW!2sph"
                      frameborder="0" style="border:0; width: 100%; height: 270px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                  </div>
      
                <!--  <!-- 菲律賓內容 -->
                  <div class="tab-pane fade" id="philippines" role="tabpanel" aria-labelledby="philippines-tab">
                      <!-- 菲律賓的 CMS 內容 -->
                      
                      <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
<div>
<h3> </h3>
<h3>地址</h3>
<p>Unit C, Bldg 87, Industrial Lot 07A-3 Partly Street, Industrial District, Tipo Hightech Ecopark, Subic Bay Freeport Zone, Philippines</p>
</div>
</div>
<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="300">
<div>
<h3>電話</h3>
<p>+886-3-3414846</p>
</div>
</div>
<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="300">
<div>
<h3>FAX</h3>
<p>+886-3-3414782</p>
</div>
</div>
<div class="info-item d-flex" data-aos="fade-up" data-aos-delay="400">
<div>
<h3>Email</h3>
<p>hongrwei24@gmail.com</p>
</div>
</div>
					  
                      
                      <!-- 菲律賓地圖 -->
                      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3861.406530023512!2d121.08214489815191!3d14.575896124122117!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3397c7e0b1138725%3A0x26974e91bb4044ed!2sTsung%20Fang%20Industrial%20Corporation!5e0!3m2!1szh-TW!2sph!4v1732419267688!5m2!1szh-TW!2sph" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                  </div>
              </div>
          </div>
      </div> 
      

   
        <div class="col-lg-7">
            <form id="contact-form" method="post" class="php-email-form" data-aos="fade-up" data-aos-delay="200">
                <input type="hidden" name="csrfmiddlewaretoken" value="UEJaRWkJIzqp9ivZZRxum5QIAgY6B1TAGM8PFFfh9M8YAMD9B15y8lkZT8PpO9wW">
                
                <div class="row gy-4 form-container" style="display: flex; height: 100%;">
<div class="col-md-6"><label class="pb-2" for="name-field"><?= $content['form_name'] ?></label> <input class="form-control" id="name-field" name="name" required type="text"></div>

<div class="col-md-6"><label class="pb-2" for="email-field"><?= $content['form_email'] ?></label> <input class="form-control" id="email-field" name="email" required type="email"></div>

<div class="col-md-12"><label class="pb-2" for="subject-field"><?= $content['form_Subject'] ?></label> <input class="form-control" id="subject-field" name="subject" required type="text"></div>

<div class="col-md-12"><label class="pb-2" for="message-field"><?= $content['form_message'] ?></label><textarea class="form-control" id="message-field" name="message" required="" rows="10"></textarea></div>

<div class="col-md-12 text-center mt-auto">
<div class="loading" style="display: none;">Loading...</div>

<div class="sent-message" style="display: none; color: green;">Your message has been sent. Thank you!</div>
<button type="submit"><?= $content['form_submit'] ?></button></div>
</div>
                
                
            </form>
        </div>

      </div>

    </div>
   

</section><!-- /Contact Section -->

<!-- 添加JavaScript -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

<script>
document.getElementById('contact-form').addEventListener('submit', function (event) {
    event.preventDefault(); // 防止表單默認提交行為

    var formData = new FormData(this); // 獲取表單數據

    // 顯示loading，隱藏其他訊息
    document.querySelector('.loading').style.display = 'block';
    document.querySelector('.sent-message').style.display = 'none';

    fetch("/zh/contactMain/contact/", {
        method: 'POST',
        body: formData,
        headers: {
            'X-CSRFToken': 'UEJaRWkJIzqp9ivZZRxum5QIAgY6B1TAGM8PFFfh9M8YAMD9B15y8lkZT8PpO9wW',
        }
    })
    .then(response => response.json())
    .then(data => {
        document.querySelector('.loading').style.display = 'none'; // 隱藏loading
        if (data.success) {
            document.querySelector('.sent-message').style.display = 'block';
            document.getElementById('contact-form').reset(); // 清空表單
        } else {
            // 這裡可以做其他的錯誤處理，比如顯示一個錯誤通知
            console.log('Error: ' + data.error); // 將錯誤訊息輸出到控制台
        }
    })
    .catch(error => {
        document.querySelector('.loading').style.display = 'none'; // 隱藏loading
        console.log('Fetch error: ' + error); // 將錯誤訊息輸出到控制台
    });
});

</script>

    
    </section><!-- /Portfolio Section -->
 
    <!-- Scroll Top -->
    <!-- <a href="#contentus" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a> -->
    <a href="#contentus" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center" >
      <i class="bi bi-bell" ></i> <!-- 使用空心鈴鐺圖標 -->
    </a>
    
 
</main>
 


</main>
		
    
   
		
	
  
    
		
		
		
		
		
		
    <footer>
        <p>&copy; 2024 <?= $content['company_name2'] ?>. <?= $content['footer_rights'] ?></p>
    </footer>


 
</body>
</html>

