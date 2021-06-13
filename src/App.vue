<template>
  <div id="app">
    <Navbar />

    <main>
      <section class="bg-lighten">
        <div class="container overflow-hidden py-5">
          <span class="badge bg-secondary px-3 mb-2">魔法科技</span>
          <h2 class="fw-bold mb-4">拍出會動的照片 | LivePhotos 魔法拍立得</h2>
          <div class="row">
            <div
              class="col-lg-7 d-flex justify-content-center align-items-center"
            >
              <img
                src="https://ecjia.com.tw/demo/bs5_homework_0526/assets/produt_image.jpg"
                alt="魔法拍立得示意圖"
                class="img-fluid rounded-5"
              />
            </div>
            <div class="col-lg-5">
              <small class="text-dark">目標 $600,000</small>
              <p class="fs-2 fw-bold mt-2 font-baloo-tamma-2">$280,047</p>
              <div class="progress rounded-pill my-3">
                <div
                  class="progress-bar text-secondary"
                  role="progressbar"
                  style="width: 41%"
                  aria-valuenow="25"
                  aria-valuemin="0"
                  aria-valuemax="100"
                >
                  41%
                </div>
              </div>
              <div class="d-flex">
                <div class="flex-fill">
                  <span>贊助人數</span>
                  <p class="fs-2 fw-bold mt-2 font-baloo-tamma-2">
                    1374 <span>人</span>
                  </p>
                </div>
                <div class="flex-fill">
                  <span>募資倒數</span>
                  <p class="fs-2 fw-bold mt-2 font-baloo-tamma-2">
                    27 <span>天</span>
                  </p>
                </div>
              </div>
              <div
                class="
                  d-flex
                  justify-content-between justify-content-md-start
                  gap-4
                  my-3
                "
              >
                <div class="icon">
                  <img
                    class="img-fluid me-1"
                    data-bs-toggle="tooltip"
                    data-bs-placement="top"
                    data-bs-original-title="認證標章"
                    src="https://hexschool.github.io/boootstrap5WebLayout/assets/icon_good01.svg"
                    alt="認證標章"
                    style="width: 24px"
                    aria-label="認證標章"
                  />
                  <small class="align-middle d-md-none">認證標章</small>
                </div>
                <div class="icon">
                  <img
                    class="img-fluid me-1"
                    data-bs-toggle="tooltip"
                    data-bs-placement="top"
                    title="品質保證"
                    src="https://hexschool.github.io/boootstrap5WebLayout/assets/icon_good02.svg"
                    alt="品質保證"
                    style="width: 24px"
                  />
                  <small class="align-middle d-md-none">品質保證</small>
                </div>
                <div class="icon">
                  <img
                    class="img-fluid me-1"
                    data-bs-toggle="tooltip"
                    data-bs-placement="top"
                    title="原生創意"
                    src="https://hexschool.github.io/boootstrap5WebLayout/assets/icon_good03.svg"
                    alt="原生創意"
                    style="width: 24px"
                  />
                  <small class="align-middle d-md-none">原生創意</small>
                </div>
                <div class="icon">
                  <img
                    class="img-fluid me-1"
                    data-bs-toggle="tooltip"
                    data-bs-placement="top"
                    title="人氣王"
                    src="https://hexschool.github.io/boootstrap5WebLayout/assets/icon_good04.svg"
                    alt="人氣王"
                    style="width: 24px"
                  />
                  <small class="align-middle d-md-none">人氣王</small>
                </div>
              </div>
              <div
                class="bg-white border-start border-3 border-primary rounded"
              >
                <p class="p-3">
                  專案募資中！<br />在
                  <span class="fw-bold">2021/06/14 23:59</span>
                  募資結束前，您都可以贊助我們！
                </p>
              </div>
              <div class="row gy-2">
                <div class="col-12">
                  <button
                    class="
                      btn btn-primary btn-primary-hover
                      w-100
                      border-2
                      rounded-pill
                      btn-lg
                      fw-bold
                    "
                  >
                    贊助專案
                  </button>
                </div>

                <div class="col-7">
                  <button
                    class="
                      btn btn-outline-secondary btn-secondary-hover
                      w-100
                      border-2
                      rounded-pill
                      btn-lg
                      fw-bold
                    "
                  >
                    <i class="fas fa-heart"></i> 追蹤專案
                  </button>
                </div>
                <div class="col-5">
                  <button
                    class="
                      btn btn-outline-secondary btn-secondary-hover
                      w-100
                      border-2
                      rounded-pill
                      btn-lg
                      fw-bold
                    "
                  >
                    <i class="fas fa-share-alt"></i> 分享
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <Nav />
    </main>

    <Footer />

    <!--  <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <!-- Modal -->
    <div
      class="modal fade"
      id="login"
      tabindex="-1"
      aria-labelledby="loginLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title fw-bold darkGray" id="loginLabel">登入</h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            <form>
              <div class="mb-3">
                <label for="account" class="form-label darkGray">帳號</label>
                <input
                  type="email"
                  class="form-control border-0"
                  id="account"
                  aria-describedby="emailHelp"
                />
              </div>
              <div class="mb-3">
                <label for="password" class="form-label darkGray">密碼</label>
                <input
                  type="password"
                  class="form-control border-0"
                  id="password"
                />
                <small class="text-secondary">忘記密碼？</small>
              </div>

              <button
                type="submit"
                class="btn btn-primary w-100 rounded-pill btn-lg fw-bold"
              >
                登入
              </button>
            </form>
            <div class="d-flex align-items-center mt-5 mb-3">
              <div class="flex-grow-1 border-bottom"></div>
              <small class="px-2"
                >還沒有帳號？<a
                  href="#"
                  class="text-danger text-decoration-none"
                  >註冊一個帳號</a
                ></small
              >
              <div class="flex-grow-1 border-bottom"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import { Tooltip } from 'bootstrap/dist/js/bootstrap.esm.min.js'
import Navbar from '@/components/Navbar'
import Footer from '@/components/Footer'
import Nav from '@/components/Nav'
export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    Nav,
  },
  methods: {},
  mounted() {
    //init tooltip
    Array.from(document.querySelectorAll('[data-bs-toggle="tooltip"]')).forEach(
      (tooltipNode) => new Tooltip(tooltipNode)
    )
  },
}
</script>

<style lang="scss">
@import '@/assets/all';
</style>
