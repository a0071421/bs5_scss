<template>
  <div>
    <section class="border-top border-bottom bg-white sticky-top">
      <div class="container">
        <ul class="nav justify-content-between justify-content-md-start">
          <li class="nav-item">
            <a
              class="nav-link py-4 px-4 active"
              data-bs-toggle="tab"
              href="#nav-intro"
              role="tab"
              aria-controls="intro"
              aria-selected="true"
              >專案介紹</a
            >
          </li>
          <li class="nav-item">
            <a
              class="nav-link py-4 px-4"
              data-bs-toggle="tab"
              href="#nav-qa"
              role="tab"
              aria-controls="qa"
              aria-selected="false"
              >常見問答</a
            >
          </li>
          <li class="nav-item">
            <a
              class="nav-link py-4 px-4"
              data-bs-toggle="tab"
              href="#nav-schedule"
              role="tab"
              aria-controls="schedule"
              aria-selected="false"
              >目前進度</a
            >
          </li>
          <li class="nav-item">
            <a
              class="nav-link py-4 px-4"
              data-bs-toggle="tab"
              href="#nav-message"
              role="tab"
              aria-controls="message"
              aria-selected="false"
              >留言</a
            >
          </li>
        </ul>
      </div>
    </section>
    <section>
      <div class="container my-5">
        <div class="row g-lg-5">
          <div class="col-lg-8">
            <div class="tab-content" id="tabContent">
              <!-- 專案介紹 -->
              <div
                class="tab-pane fade show active mb-5 mb-lg-0"
                id="nav-intro"
                role="tabpanel"
                aria-labelledby="nav-intro-tab"
              >
                <img
                  class="img-fluid w-100"
                  src="https://hexschool.github.io/boootstrap5WebLayout/assets/p1.jpg"
                  alt="施了魔法的照片"
                />
                <h3
                  class="
                    h4
                    fw-bold
                    border-start border-4 border-primary
                    px-3
                    mt-3
                  "
                >
                  施了魔法的照片
                </h3>
                <p class="lh-lg text-justify mb-4">
                  受就相法大夠局來畫師我只這然以放灣得的後人心年我物我年，或人有動與次出女親構算帶年行著所間女，外成認心香吸工並知日成展源大超時動為生葉衣致長山對精做英密差家他微熱建取示濟定心一，品定把別銀動，深青輪一物加，生明果。西業白老如天有表非民大條全那遊，李文遊、像香過元學須本致信校態麼資司媽人價在它，地他不我計孩廠然不大指勢生的華常簡岸然，人著母病石金萬得一果。
                </p>
                <img
                  class="img-fluid w-100"
                  src="https://hexschool.github.io/boootstrap5WebLayout/assets/p2.jpg"
                  alt="留下當下的美好"
                />
                <h3
                  class="
                    h4
                    fw-bold
                    border-start border-4 border-primary
                    px-3
                    mt-3
                  "
                >
                  留下當下的美好
                </h3>
                <p class="lh-lg text-justify mb-4">
                  受就相法大夠局來畫師我只這然以放灣得的後人心年我物我年，或人有動與次出女親構算帶年行著所間女，外成認心香吸工並知日成展源大超時動為生葉衣致長山對精做英密差家他微熱建取示濟定心一，品定把別銀動，深青輪一物加，生明果。西業白老如天有表非民大條全那遊，李文遊、像香過元學須本致信校態麼資司媽人價在它，地他不我計孩廠然不大指勢生的華常簡岸然，人著母病石金萬得一果。
                </p>
              </div>
              <!-- 常見問題 -->
              <div
                class="tab-pane fade mb-5 mb-lg-0"
                id="nav-qa"
                role="tabpanel"
                aria-labelledby="nav-ga-tab"
              >
                <ul class="accordion list-unstyled" id="accordionQA">
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ1">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ1"
                        aria-expanded="false"
                        aria-controls="accordionQ1"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q1</span
                        >
                        影片拍完之後可以編輯嗎？
                      </button>
                    </h2>
                    <div
                      id="accordionQ1"
                      class="accordion-collapse collapse"
                      aria-labelledby="headingQ1"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        可以進行簡易的編輯，內建 5
                        種濾鏡，影片秒數有3秒、5秒、10秒可以選擇，拍完的當下可以編輯要印出來的影片範圍哦！
                      </div>
                    </div>
                  </li>
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ2">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ2"
                        aria-expanded="false"
                        aria-controls="accordionQ2"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q2</span
                        >
                        有提供保固或維修服務嗎？
                      </button>
                    </h2>
                    <div
                      id="accordionQ2"
                      class="accordion-collapse collapse"
                      aria-labelledby="headingQ2"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        提供產品售後服務，對產品本體(不含配件、線材)提供二年保固服務。產品因意外或人為不當使用或未經授權維修等非依使用手冊使用而造成產品損壞者，則不在保固範圍之內，得向客戶酌收產品維修服務費用。
                      </div>
                    </div>
                  </li>
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ3">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ3"
                        aria-expanded="false"
                        aria-controls="accordionQ3"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q3</span
                        >
                        補充包底片要去哪裡購買呢？
                      </button>
                    </h2>
                    <div
                      id="accordionQ3"
                      class="accordion-collapse collapse"
                      aria-labelledby="headingQ3"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        本產品可以兼容 i-type 及 600
                        相片，各大網路平台皆有販售。
                      </div>
                    </div>
                  </li>
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ4">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ4"
                        aria-expanded="false"
                        aria-controls="accordionQ4"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q4</span
                        >
                        印出來的拍立得照片需要充電嗎？
                      </button>
                    </h2>
                    <div
                      id="accordionQ4"
                      class="accordion-collapse border rounded collapse"
                      aria-labelledby="headingQ4"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        不用，取出後稍微搖晃，相片與空氣接觸數秒後便會產生圖像顏色。
                      </div>
                    </div>
                  </li>
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ5">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ5"
                        aria-expanded="false"
                        aria-controls="accordionQ5"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q5</span
                        >
                        運送方式及付款方式有哪些呢？
                      </button>
                    </h2>
                    <div
                      id="accordionQ5"
                      class="accordion-collapse border rounded collapse"
                      aria-labelledby="headingQ5"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        可以選擇超商取貨及宅配，付款方式有銀行轉帳及信用卡支付。
                      </div>
                    </div>
                  </li>
                  <li class="accordion-item border rounded mb-3">
                    <h2 class="accordion-header" id="headingQ6">
                      <button
                        class="accordion-button background-none collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#accordionQ6"
                        aria-expanded="false"
                        aria-controls="#accordionQ6"
                      >
                        <span
                          class="
                            badge
                            bg-primary
                            p-2
                            me-2
                            fw-bold
                            font-baloo-tamma-2
                          "
                          >Q6</span
                        >
                        退換貨方式及規則
                      </button>
                    </h2>
                    <div
                      id="accordionQ6"
                      class="accordion-collapse collapse"
                      aria-labelledby="headingQ6"
                      data-bs-parent="#accordionQA"
                    >
                      <div class="accordion-body">
                        因商品封條多為一次性包裝，商品退貨時必須回復原狀，亦即必須回復至您收到商品時的原始狀態，且會視回收的商品狀態另外酌收額外的整新費用，請您務必確認有購買需求後再行拆封，感謝您的配合。。
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
              <!-- 目前進度 -->
              <div
                class="tab-pane fade mb-5 mb-lg-0"
                id="nav-schedule"
                role="tabpanel"
                aria-labelledby="nav-schedule-tab"
              >
                <ul class="now-progress list-unstyled">
                  <li>
                    <div class="card mb-3">
                      <div class="row g-0">
                        <div class="col-4">
                          <img
                            class="img-fluid h-100"
                            src="https://hexschool.github.io/boootstrap5WebLayout/assets/news01.jpg"
                            alt="目前進度-1"
                          />
                        </div>
                        <div class="col-8">
                          <div class="card-body">
                            <h4 class="card-title fs-6 fw-bold">
                              高雄體驗會｜免費參加送帆布袋
                            </h4>
                            <small class="text-secondary font-baloo-tamma-2"
                              >2021-6-20</small
                            >

                            <p class="card-text text-secondary text-justify">
                              <small
                                >大家安安！謝謝每位贊助者的熱情支持，讓我們離夢想更進一步，我們將於下個月舉辦體驗會，歡迎各位踴躍參與！</small
                              >
                            </p>
                            <a
                              href="#"
                              class="
                                text-decoration-none text-red
                                fw-bold
                                font-baloo-tamma-2
                              "
                              ><small>More</small></a
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="card mb-3">
                      <div class="row g-0">
                        <div class="col-4">
                          <img
                            class="img-fluid h-100"
                            src="https://hexschool.github.io/boootstrap5WebLayout/assets/news02.jpg"
                            alt="目前進度-2"
                          />
                        </div>
                        <div class="col-8">
                          <div class="card-body">
                            <h4 class="card-title fs-6 fw-bold">
                              高雄體驗會｜免費參加送帆布袋
                            </h4>
                            <small class="text-secondary font-baloo-tamma-2"
                              >2021-6-20</small
                            >

                            <p class="card-text text-secondary text-justify">
                              <small
                                >大家安安！謝謝每位贊助者的熱情支持，讓我們離夢想更進一步，我們將於下個月舉辦體驗會，歡迎各位踴躍參與！</small
                              >
                            </p>
                            <a
                              href="#"
                              class="
                                text-decoration-none text-red
                                fw-bold
                                font-baloo-tamma-2
                              "
                              ><small>More</small></a
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li>
                    <div class="card mb-3">
                      <div class="row g-0">
                        <div class="col-4">
                          <img
                            class="img-fluid h-100"
                            src="https://hexschool.github.io/boootstrap5WebLayout/assets/news03.jpg"
                            alt="目前進度-3"
                          />
                        </div>
                        <div class="col-8">
                          <div class="card-body">
                            <h4 class="card-title fs-6 fw-bold">
                              高雄體驗會｜免費參加送帆布袋
                            </h4>
                            <small class="text-secondary font-baloo-tamma-2"
                              >2021-6-20</small
                            >

                            <p class="card-text text-secondary text-justify">
                              <small
                                >大家安安！謝謝每位贊助者的熱情支持，讓我們離夢想更進一步，我們將於下個月舉辦體驗會，歡迎各位踴躍參與！</small
                              >
                            </p>
                            <a
                              href="#"
                              class="
                                text-decoration-none text-red
                                fw-bold
                                font-baloo-tamma-2
                              "
                              ><small>More</small></a
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
              <!-- 留言 -->
              <div
                class="tab-pane fade mb-5 mb-lg-0"
                id="nav-message"
                role="tabpanel"
                aria-labelledby="nav-message-tab"
              >
                <div
                  class="
                    bg-gray-100
                    border-start border-primary border-3
                    rounded
                    px-3
                    py-3
                    letter-spacing-sm
                  "
                >
                  只有本專案的贊助者才可以留言哦，如果有任何專案相關的問題，歡迎<a
                    href="#"
                    class="text-red text-decoration-none"
                    >聯絡提案人</a
                  >！
                </div>
                <ul class="list-unstyled my-3">
                  <li class="mb-3">
                    <div class="card">
                      <div class="d-flex align-items-center p-3 pb-0">
                        <img
                          class="flex-shrink-0"
                          src="https://hexschool.github.io/boootstrap5WebLayout/assets/user_img01.jpg"
                          alt="user1"
                        />
                        <div class="flex-grow-1 ms-3">
                          <h4 class="fw-bold letter-spacing-md">廖小杰</h4>
                          <small class="text-secondary letter-spacing-md"
                            >2021年6月2日 20:32</small
                          >
                        </div>
                      </div>
                      <div class="card-body">
                        <p class="card-text">
                          晚上起床上廁所看到照片裡的人一直動其實有點恐怖，希望可以有暫停或是定時的功能！
                        </p>
                        <div class="bg-gray-200 rounded p-3">
                          <small class="text-red">提案者回覆</small>
                          <p class="mt-2 mb-0">
                            你要嘛起床的時候開燈，要嘛給我們更多錢開發阿
                          </p>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <div class="card">
                      <div class="d-flex align-items-center p-3 pb-0">
                        <img
                          class="flex-shrink-0"
                          src="https://hexschool.github.io/boootstrap5WebLayout/assets/user_img02.jpg"
                          alt="user2"
                        />
                        <div class="flex-grow-1 ms-3">
                          <h4 class="fw-bold letter-spacing-md">卡阿伯</h4>
                          <small class="text-secondary letter-spacing-md"
                            >2021年5月28日 00:32</small
                          >
                        </div>
                      </div>
                      <div class="card-body">
                        <p class="card-text">
                          希望有更多花色可以選擇！我女兒最近喜歡綠色
                        </p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <div class="card">
                      <div class="d-flex align-items-center p-3 pb-0">
                        <img
                          class="flex-shrink-0"
                          src="https://hexschool.github.io/boootstrap5WebLayout/assets/user_img02.jpg"
                          alt="user2"
                        />
                        <div class="flex-grow-1 ms-3">
                          <h4 class="fw-bold letter-spacing-md">賈師</h4>
                          <small class="text-secondary letter-spacing-md"
                            >2021年5月15日 08:32</small
                          >
                        </div>
                      </div>
                      <div class="card-body">
                        <p class="card-text">
                          可以做個相簿功能嗎？拍出好看的影片再讓我們選擇要印出哪一張這樣
                        </p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <div class="card">
                      <div class="d-flex align-items-center p-3 pb-0">
                        <img
                          class="flex-shrink-0"
                          src="https://hexschool.github.io/boootstrap5WebLayout/assets/user_img02.jpg"
                          alt="user2"
                        />
                        <div class="flex-grow-1 ms-3">
                          <h4 class="fw-bold letter-spacing-md">俊俊</h4>
                          <small class="text-secondary letter-spacing-md"
                            >2021年5月2日 21:55</small
                          >
                        </div>
                      </div>
                      <div class="card-body">
                        <p class="card-text">
                          test123 看一下我是不是真的可以留言
                        </p>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>

            <section class="mb-5 d-lg-none">
              <Sidebar />
            </section>

            <Sponsor />
          </div>
          <div class="col-lg-4 d-none d-lg-block">
            <div class="position-sticky sticky-nav h-nav overflow-scroll">
              <Sidebar />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Sidebar from '@/components/Sidebar'
import Sponsor from '@/components/Sponsor'
export default {
  name: 'Nav',
  components: {
    Sidebar,
    Sponsor,
  },
}
</script>
