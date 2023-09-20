<template>
    <!-- <div>
        <div class="header header-classic header-lg">
            <div class="mid-bar navbar-nav">
              <div class="icons-wrapper">
                <div class="desktop-logo-wrapper">
                  <div class="logo">
                    <a href="https://myshoes.vn/index.php?route=common/home">
                      <img
                        src="https://myshoes.vn/image/cache/catalog/logo/logo_ms-565x195.png"
                        srcset="
                          https://myshoes.vn/image/cache/catalog/logo/logo_ms-565x195.png 1x,
                          https://myshoes.vn/image/cache/catalog/logo/logo_ms-565x195.png 2x
                        "
                        alt="Myshoes.vn - Giày Chính Hãng"
                        title="Myshoes.vn - Giày Chính Hãng"
                      />
                    </a>
                  </div>
                </div>
                <div class="search-input-wrapper">
                  <input type="text" class="search-input" placeholder="Tìm kiếm sản phẩm..." />
                  <div class="search-icon"><i class="fas fa-search"></i></div>
                </div>
        
                <div class="account-cart-wrapper">
                  <a href="https://myshoes.vn/login" class="dropdown-toggles" data-toggle="dropdown">
                    <div class="account-icon"><i class="fas fa-user"></i></div>
                    <div class="account-text">
                      <span class="account-label">Tài khoản</span>
                      <span class="login-register">Đăng nhập / Đăng ký</span>
                    </div>
                  </a>
        
                  <div class="desktop-cart-wrapper default-cart-wrapper">
                    <div id="cart" class="dropdown">
                      <a
                        data-toggle=""
                        data-loading-text="Đang Xử lý..."
                        class="dropdown-toggle cart-heading"
                        href="https://myshoes.vn/index.php?route=checkout/cart"
                        aria-expanded="false"
                      >
                        <i class="fa fa-shopping-cart cart-icon"></i>
                         Thêm biểu tượng giỏ hàng -->
                        <!-- <span id="cart-total"></span>
                        <span id="cart-items" class="count-badge count-zero">0</span>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="desktop-main-menu-wrapper menu-default has-menu-2 navbar-nav">
              <div id="main-menu" class="main-menu main-menu-291">
                <ul class="j-menu">
                  <li class="menu-item main-menu-item main-menu-item-2 multi-level dropdown drop-menu first-dropdown">
                    <a href="https://myshoes.vn/giay-nike" class="dropdown-toggle" data-toggle="dropdown">
                      <span class="links-text">Giày Nike</span>
                      <span class="menu-label">New</span>
                    </a>
                    <div class="dropdown-menu" id="collapse-64e4312d01baa">
                      <ul class="j-menus">
                        <li class="menu-items ">
                          <a href="https://myshoes.vn/giay-nike-nam"><i class="horizontal-arrow-icon">→</i><span class="links-texts">Giày Nike Nam</span></a>
                        </li>
                        <hr>
                        <li class="menu-items ">
                          <a href="https://myshoes.vn/giay-nike-nu"><i class="horizontal-arrow-icon">→</i><span class="links-texts">Giày Nike Nữ</span></a>
                        </li>
                      </ul>
                    </div>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-5 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-adidas">
                      <span class="links-text">Giày Adidas</span>
                      <span class="menu-labels">Sale</span>
                    </a>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-6 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-lacoste">
                      <span class="links-text">Giày Lacoste</span>
                      <span class="menu-label">New</span>
                    </a>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-7 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-puma">
                      <span class="links-text">Giày Puma</span>
                      <span class="menu-labels">Sale</span>
                    </a>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-8 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-new-balance">
                      <span class="links-text">Giày New Balance</span>
                      <span class="menu-label">New</span>
                    </a>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-9 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-asics">
                      <span class="links-text">Giày Asics</span>
                      <span class="menu-label">New</span>
                    </a>
                  </li>
                  <li class="menu-item main-menu-item main-menu-item-12 multi-level drop-menu">
                    <a href="https://myshoes.vn/giay-the-thao-chinh-hang">
                      <span class="links-text">Giày Thể Thao</span>
                    </a>
                  </li>
                  <li class="menu-item-sale main-menu-item main-menu-item-13 multi-level drop-menu">
                    <a href="https://myshoes.vn/sieu-sale">
                      <span class="sale">SALE</span>
                    </a>
                  </li>
                  <li class="menu-item-lienhe main-menu-item main-menu-item-13 multi-level drop-menu">
                      <Icon class="icon-email"  icon="carbon:email" />
                    <a href="https://myshoes.vn/sieu-sale">
                      <span class="links-text">Liên hệ</span>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
    </div> --> 
    <nav class="colorlib-nav" role="navigation">
			<div class="top-menu">
				<div class="container">
					<div class="row">
						<div class="col-sm-6 col-md-6">
							<div id="colorlib-logo"><a href="index.html">Footwear</a></div>
						</div>
						<div class="col-sm-3 col-md-3">
							<form class="search-wrap">
								<div class="form-group">
									<input type="search" class="form-control search" placeholder=" Tìm Kiếm">
									<button class="btn btn-primary submit-search text-center" type="submit"><i
											class="icon-search"></i></button>
								</div>
							</form>
						</div>
						<div class="col-sm-3 col-md-3">
							<form class="search-wrap">
								<div class="form-group">
									<button class="btn btn-primary submit-search text-center" style="width: 100px;margin-left: 140px;position: relative;"
										type="submit"><i><a href="login.html" style="color: aliceblue;">Tài Khoản</a></i></button>
								</div>
							</form>
						</div>
					</div>

					<div class="row">
						<div class="col-sm-12 text-left menu-1">
							<ul>
								<li class="active"><a href="index.html">Trang Chủ</a></li>
								<li class="has-dropdown">
									<a href="men.html">Giày Nam</a>
									<ul class="dropdown">
										<li><a href="product-detail.html">Chi Tiết Sản Phẩm</a></li>
										<li><a href="cart.html">Giỏ Hàng</a></li>
										<li><a href="checkout.html">Thanh Toán</a></li>

									</ul>
								</li>
								<li><a href="women.html">Giày Nữ</a></li>
								<li><a href="about.html">Giới Thiệu</a></li>
								<li><a href="contact.html">Liên Hệ</a></li>
								<li class="cart"><a href="cart.html"><i class="icon-shopping-cart"></i> Cart[0]</a>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</nav>
</template>
<script setup lang="ts"> 
</script>
<style lang="">
    
</style>