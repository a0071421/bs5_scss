<template>
  <section class="sponsor">
    <div class="text-center">
      <img
        src="https://hexschool.github.io/boootstrap5WebLayout/assets/icon_heart.svg"
        alt="icon_heart"
      />
    </div>
    <div class="d-flex align-items-center mt-1 mb-3">
      <div class="flex-grow-1 border-bottom border-primary border-3"></div>
      <h2 class="h4 fw-bold px-3">贊助專案</h2>
      <div class="flex-grow-1 border-bottom border-primary border-3"></div>
    </div>
    <form class="needs-validation" novalidate>
      <div class="mb-3">
        <label for="sponsorCase" class="form-label darkGray">贊助方案</label>
        <select
          id="sponsorCase"
          class="form-select border-0"
          aria-label="select sponsorCase"
          required
        >
          <option value="">請選擇一種方案</option>
          <option value="1">方案1</option>
          <option value="2">方案2</option>
          <option value="3">方案3</option>
        </select>
        <div class="invalid-feedback">請選擇一個方案</div>
      </div>
      <div class="mb-3">
        <label for="name" class="form-label darkGray">收件人姓名</label>
        <input
          type="text"
          class="form-control border-0"
          id="name"
          aria-describedby="name"
          required
        />
        <div class="invalid-feedback">請輸入收件人姓名</div>
      </div>
      <div class="mb-3">
        <label for="address" class="form-label darkGray">收件地址</label>
        <input
          type="text"
          class="form-control border-0"
          id="address"
          aria-describedby="address"
          required
        />
        <div class="invalid-feedback">請輸入收件地址</div>
      </div>
      <div class="mb-3">
        <label for="phone" class="form-label darkGray">聯絡電話</label>
        <input
          type="tel"
          class="form-control border-0"
          id="phone"
          aria-describedby="phone"
          required
        />
        <div class="invalid-feedback">請輸入連絡電話</div>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label darkGray">聯絡信箱</label>
        <input
          type="email"
          class="form-control border-0"
          id="email"
          aria-describedby="email"
          required
        />
        <div class="invalid-feedback">請輸入聯絡信箱</div>
      </div>

      <div class="mb-3">
        <label for="payment" class="form-label darkGray">付款方式</label>
        <select
          id="payment"
          class="form-select border-0"
          aria-label="select payment"
          required
        >
          <option value="">請選擇一種付款方式</option>
          <option value="cash">貨到付款</option>
          <option value="creditCard">信用卡付款</option>
        </select>
        <div class="invalid-feedback">請選擇付款方式</div>
      </div>

      <div class="text-center">
        <button
          type="submit"
          class="btn btn-primary btn-lg rounded-pill fw-bold px-5 py-2"
        >
          贊助專案
        </button>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  name: 'Sponsor',
  mounted() {
    ;(function () {
      'use strict'
      var forms = document.querySelectorAll('.needs-validation')
      Array.prototype.slice.call(forms).forEach(function (form) {
        form.addEventListener(
          'submit',
          function (event) {
            if (!form.checkValidity()) {
              event.preventDefault()
              event.stopPropagation()
            }
            form.classList.add('was-validated')
          },
          false
        )
      })
    })()
  },
}
</script>
