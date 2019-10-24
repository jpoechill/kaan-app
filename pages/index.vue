<template>
  <div class="container mt-4">
    <div class="row height-600">
      <div class="col-md-3">
        <h3>
          <nuxt-link to="/" class="playfair-heavy">Justifact</nuxt-link>
        </h3>
        Beyka | Logout

        <br><br>

        <button class="form-control w-100 mb-3">Add New Product</button>
        <nuxt-link to="/">Gabriella Plants</nuxt-link> <span class="float-right">548</span><br />
        <nuxt-link to="/">Galatea</nuxt-link> <span class="float-right">42</span><br />
        <nuxt-link to="/">Galatia</nuxt-link> <span class="float-right">36</span><br />
        <nuxt-link to="/">Galaxy</nuxt-link> <span class="float-right">89</span><br />
        <nuxt-link to="/">Galba</nuxt-link> <span class="float-right">42</span><br />
        <nuxt-link to="/">Gale</nuxt-link> <span class="float-right">36</span><br />
        <nuxt-link to="/">Galacia</nuxt-link> <span class="float-right">89</span><br />
        <nuxt-link to="/">Galacian</nuxt-link> <span class="float-right">42</span><br />
        <nuxt-link to="/">Galile</nuxt-link> <span class="float-right">36</span><br />
        <nuxt-link to="/">Galileo</nuxt-link> <span class="float-right">89</span><br />
        <br>
        <select class="custom-select">
          <option selected>Alphabetical Order</option>
          <option value="1">Trending Order</option>
        </select>
      </div>

      <div class="col-md-9">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <input type="text" class="w-100 p-2 mb-4" placeholder="Search for something...">
            </div>
          </div>
          <div class="row">
            <div class="col-md-8">
              <h1 class="playfair-heavy">Gabriella Plants</h1>
              Tags: Tag 1, Tag 2, Tag 3 <br>
              Tally: 2,116 (^ 2,351 V 235)<br>
            </div>
            <div class="col-md-4">
            </div>
          </div>
        </div>

        <div class="container">
          <div class="row mt-4 mb-2">
            <div class="col-md-12">Top Review</div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div class="container px-0 pb-5">
                <div class="row">
                  <div class="col-md-12">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt quae inventore similique delectus ullam tenetur perferendis. Maxime, magni numquam! Aut adipisci, id qui expedita exercitationem autem dolorem laboriosam ipsam tenetur voluptates aliquam possimus non recusandae dolore omnis quidem officia perferendis cum dolores nihil beatae! Officiis, dolorem quisquam alias ratione tempora dolore aliquid quo unde. Dolore qui deserunt minus excepturi quia!
                    <br><br>
                    Monroe <br>
                    (212) 98% Positive <br>
                    Online 9 hours ago
                  </div>
                  <!-- <div class="col-md-6">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt quae inventore similique delectus ullam tenetur perferendis. Maxime, magni numquam! Aut adipisci, id qui expedita exercitationem autem dolorem laboriosam ipsam tenetur voluptates aliquam possimus non recusandae dolore omnis quidem officia perferendis cum dolores nihil beatae! Officiis, dolorem quisquam alias ratione tempora dolore aliquid quo unde. Dolore qui deserunt minus excepturi quia!
                    <br><br>
                    Monroe <br>
                    (212) 98% Positive <br>
                    Online 9 hours ago
                  </div> -->
                </div>
                <div class="row mt-5">
                  <div class="col-md-12">
                    Sort: Most "Positive"
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-4 pt-3">
                    <div class="">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. A est cumque amet ipsa ea repellat blanditiis quos delectus dolor id praesentium pariatur nesciunt, nostrum nam quibusdam dolorem provident, eaque ut.
                      <br><br>
                      Monroe <br>
                      (212) 98% Positive <br>
                      Online 9 hours ago
                    </div>
                  </div>
                  <div class="col-md-4 pt-3">
                    <div class="">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum enim obcaecati veritatis eveniet exercitationem recusandae assumenda laborum id! Qui voluptas cupiditate natus odio sit error dicta aperiam neque ullam reprehenderit.
                      <br><br>
                      Monroe <br>
                      (212) 98% Positive <br>
                      Online 9 hours ago
                    </div>
                  </div>
                  <div class="col-md-4 pt-3">
                    <div class="">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque eius saepe, earum in incidunt deserunt ipsum nam officiis doloribus facilis, nemo totam voluptates quae hic rerum tempora, illum excepturi sunt.
                      <br><br>
                      Monroe <br>
                      (212) 98% Positive <br>
                      Online 9 hours ago
                    </div>
                  </div>
                  <div class="col-md-4 pt-3">
                    <div class="">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique culpa earum, aliquam dicta ab voluptate recusandae reiciendis odit voluptatem exercitationem. Ut nam delectus vel voluptas commodi nihil quam ex iusto!
                      <br><br>
                      Monroe <br>
                      (212) 98% Positive <br>
                      Online 9 hours ago
                    </div>
                  </div>
                  <div class="col-md-4 pt-3">
                    <div class="">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur quo optio nesciunt cum corporis recusandae. Fugiat modi eum corporis ipsum quod possimus magnam eos adipisci, natus fugit deserunt atque quibusdam?
                      <br><br>
                      Monroe <br>
                      (212) 98% Positive <br>
                      Online 9 hours ago
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="container">
          <div class="row">
            <div class="col-md-12 pt-4">
              <input type="text" class="form-control mb-3 w-100" placeholder="Add your opinion...">
              <!-- <button>Add Image</button> -->
              <button class="form-control">Leave Review</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>

<style>
</style>
