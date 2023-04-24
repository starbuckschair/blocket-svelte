<script>
	import Navbar from '../components/Navbar.svelte';
</script>

<Navbar />
<div class="home-area">
	<div class="d-table">
		<div class="d-table-cell">
			<div class="container">
				<div class="row align-items-center">
					<div class="col-lg-6 col-md-12">
						<div class="main-banner-content">
							<h1>IT Solutions & Business Services Company</h1>
							<p>
								SW, HW, 컨텐츠 분야의 여러 전문업체들과 협력관계를 통한<br />
								<strong>시스템 통합(SI), IT Outsorcing, 컨설팅 등</strong>
								을 진행하고 있습니다. <br /><br />
								블록체인, AI와 사상적 기반을 함께하는 서비스를 위한
								<br />
								<strong> 블록체인 연동형 POS시스템, NFT MarketPlace</strong>
								등을<br /> 핵심분야로 하여 다양한 사업을 진행하고 있습니다.
							</p>
							<div class="banner-btn">
								<a class="default-btn-one" href="services.html">
									Our Service
									<span />
								</a>
								<a class="default-btn-two" href="contact.html">
									Contact Us
									<span />
								</a>
							</div>
						</div>
					</div>
					<div class="col-lg-6 col-md-12">
						<div class="banner-image">
							<img src="assets/img/home-font.png" alt="image" />
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="creative-shape">
		<img src="assets/img/home-bottom-shape.png" alt="svg shape" />
	</div>
</div>

<div>
    <div>타일6개</div>
    <div>타일6개 큰 제목</div>
    <div class= "row row-cols-3">
        <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
          <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
          <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
          <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
          <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>
          <div class="card" style="col;">
            <img src="..." class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div>

    </div>

</div>

<div class="service-info">
    <div class="card" style="width: 18rem;">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        </div>
      </div>
</div>


<style lang="scss">
    .card-div {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    .service-info {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
</style>