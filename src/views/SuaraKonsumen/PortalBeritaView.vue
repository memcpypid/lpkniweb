<template>
  <div class="bg-gray-200">
    <!-- Header Section -->
    <NavbarNews />

<section class="container mx-auto px-4 py-12 bg-white rounded-lg shadow-md mb-8 mt-7">
  <div class="flex flex-col md:flex-row items-center space-y-6 md:space-y-0 md:space-x-6">
    <!-- Banner Image -->
    <div class="w-full md:w-1/2">
      <img src="@/assets/bannerberita.jpeg" alt="Trending Image" class="w-full h-auto object-cover rounded-lg"/>
    </div>

    <!-- News Content -->
    <div class="flex flex-col justify-between space-y-4 w-full md:w-1/2">
      <div>
        <!-- Breaking News Alert -->
        <div class="bg-red-600 text-white p-2 rounded-lg inline-block mb-4">
          <span class="font-bold text-sm">Breaking News</span>
        </div>
        <!-- Title -->
        <h2 class="text-3xl font-bold text-gray-900 leading-tight">
          Cake meme reflects coronavirus absurdity in a world where nothing is what it seems
        </h2>
        <!-- Description -->
        <p class="text-gray-700 text-sm mt-2">
          Earlier this month, a viral video depicting hyper-realistic cakes as everyday items had folks on social media double-guessing every other post, and sometimes even their own realities...
        </p>
        <div class="mt-4">
          <p class="text-xs text-gray-500">2 hours ago | By Lucy Hiddleston | 4 min read</p>
        </div>
        <!-- Read More Button -->
        <router-link :to="'/news/1'">
          <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
        </router-link>
      </div>
    </div>
  </div>
</section>


    <!-- Main Content Section -->
    <div class="container mx-auto px-6 py-6 md:px-8 sm:px-8">
      <div class="bg-red-600 text-white p-4 rounded-lg mb-8">
        <h3 class="font-semibold text-lg">TANG MUNGKIN ANDA SUKA....</h3>
        <p class="text-sm">Beberapa berita ekslusif....</p>
      </div>

      <!-- Trending Section -->
      <section class="mb-8">
    <h2 class="text-xl font-semibold mb-4">Trending</h2>
    <div class="flex flex-wrap sm:flex-nowrap sm:space-x-6 space-y-6 sm:space-y-0">
      <!-- Card 1 -->
      <div class="w-full sm:w-1/3">
        <img src="@/assets/bannerberita.jpeg" alt="Trending Image" class="w-full h-48 object-cover rounded-lg mb-4" />
        <h3 class="text-lg font-semibold">Cake meme reflects coronavirus absurdity in a world where nothing is what it seems</h3>
        <p class="text-sm text-gray-700">Earlier this month, a viral video depicting hyper-realistic cakes as everyday items had folks on social media double-guessing every other post...</p>
        <router-link :to="'/news/1'">
          <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
        </router-link>
      </div>

      <!-- Card 2 -->
      <div class="w-full sm:w-1/3">
        <img src="@/assets/bannerberita.jpeg" alt="Trending Image" class="w-full h-48 object-cover rounded-lg mb-4" />
        <h3 class="text-lg font-semibold">John Lewis' final journey across Edmund Pettus Bridge in procession</h3>
        <p class="text-sm text-gray-700">The body of the late US Rep. John Lewis on Sunday will make the final journey across the famous bridge in Selma, Alabama...</p>
        <router-link :to="'/news/1'">
          <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
        </router-link>
      </div>

      <!-- Card 3 -->
      <div class="w-full sm:w-1/3">
        <img src="@/assets/bannerberita.jpeg" alt="Trending Image" class="w-full h-48 object-cover rounded-lg mb-4" />
        <h3 class="text-lg font-semibold">John Lewis' final journey across Edmund Pettus Bridge in procession</h3>
        <p class="text-sm text-gray-700">The body of the late US Rep. John Lewis on Sunday will make the final journey across the famous bridge in Selma, Alabama...</p>
        <router-link :to="'/news/1'">
          <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
        </router-link>
      </div>
    </div>
  </section>

      <!-- Section Baru -->
      <section class="container mx-auto px-4 py-6">
    <div class="flex flex-col sm:flex-row space-y-6 sm:space-y-0 sm:space-x-6">
      <!-- Left Section (Featured Article) -->
      <div class="w-full sm:w-2/3 bg-gray-100 rounded-lg shadow-md">
        <img src="@/assets/bannerberita.jpeg" alt="Featured Article Image" class="w-full h-64 object-cover rounded-t-lg" />
        <div class="p-4">
          <h3 class="text-2xl sm:text-3xl font-bold text-gray-900">Beloved Arizona coach loses battle with coronavirus</h3>
          <p class="text-xs sm:text-sm text-gray-600 mt-2">The body of the late US Rep. John Lewis on Sunday will make the final journey across the famous bridge in Selma, Alabama.</p>
          <div class="text-xs sm:text-sm text-gray-500 mt-4">1 Maret 2024</div>
          <!-- Baca Selengkapnya Button -->
          <router-link :to="'/news/1'">
            <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
          </router-link>
        </div>
      </div>

      <!-- Right Section (Smaller Articles) -->
      <div class="w-full sm:w-1/3 space-y-6">
        <!-- Smaller Article 1 -->
        <div class="flex space-x-4">
          <img src="@/assets/bannerberita.jpeg" alt="Article 1" class="w-1/3 sm:w-1/4 h-20 object-cover rounded-lg" />
          <div class="w-2/3 sm:w-3/4">
            <h4 class="text-lg font-semibold text-gray-800">John Lewis, civil rights giant</h4>
            <p class="text-xs sm:text-sm text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum repellendus aperiam quasi!</p>
            <!-- Baca Selengkapnya Button -->
            <router-link :to="'/news/1'">
              <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
            </router-link>
          </div>
        </div>

        <!-- Smaller Article 2 -->
        <div class="flex space-x-4">
          <img src="@/assets/bannerberita.jpeg" alt="Article 2" class="w-1/3 sm:w-1/4 h-20 object-cover rounded-lg" />
          <div class="w-2/3 sm:w-3/4">
            <h4 class="text-lg font-semibold text-gray-800">Beloved Arizona coach loses battle with coronavirus</h4>
            <p class="text-xs sm:text-sm text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis exercitationem architecto suscipit.</p>
            <!-- Baca Selengkapnya Button -->
            <router-link :to="'/news/1'">
              <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
            </router-link>
          </div>
        </div>

        <!-- Smaller Article 3 -->
        <div class="flex space-x-4">
          <img src="@/assets/bannerberita.jpeg" alt="Article 3" class="w-1/3 sm:w-1/4 h-20 object-cover rounded-lg" />
          <div class="w-2/3 sm:w-3/4">
            <h4 class="text-lg font-semibold text-gray-800">Beloved Arizona coach loses battle with coronavirus</h4>
            <p class="text-xs sm:text-sm text-gray-500">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eius esse labore dignissimos.</p>
            <!-- Baca Selengkapnya Button -->
            <router-link :to="'/news/1'">
              <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </section>

       <!-- Latest Stories Section -->
       <section class="mb-8">
        <h2 class="text-xl font-semibold mb-4">Berita Nasional...</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
          <article class="bg-white p-4 rounded-lg shadow-md">
            <img src="@/assets/bahlil.jpeg" alt="Latest Story" class="w-full h-56 object-cover rounded-md mb-4"/>
            <h3 class="text-lg font-semibold">John Lewis makes final journey across Edmund Pettus Bridge</h3>
            <p class="text-sm text-gray-700">The body of the late US Rep. John Lewis on Sunday will make the final journey across the famous bridge in Selma, Alabama...</p>
           <!-- Contoh dengan route statis -->
          <router-link :to="'/news/1'">
            <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
          </router-link>

          </article>
          <article class="bg-white p-4 rounded-lg shadow-md">
            <img src="@/assets/bahlil.jpeg" alt="Latest Story" class="w-full h-56 object-cover rounded-md mb-4"/>
            <h3 class="text-lg font-semibold">John Lewis, civil rights giant, crosses Edmund Pettus Bridge one final time</h3>
            <p class="text-sm text-gray-700">Solemn crowds watch as Lewis, who died earlier this month at the age of 80, is borne by caisson over Edmund Pettus Bridge...</p>
         <!-- Contoh dengan route statis -->
        <router-link :to="'/news/1'">
          <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
        </router-link>

          </article>
          <article class="bg-white p-4 rounded-lg shadow-md">
            <img src="@/assets/bahlil.jpeg" alt="Latest Story" class="w-full h-56 object-cover rounded-md mb-4"/>
            <h3 class="text-lg font-semibold">John Lewis, civil rights giant, crosses Edmund Pettus Bridge one final time</h3>
            <p class="text-sm text-gray-700">Solemn crowds watch as Lewis, who died earlier this month at the age of 80, is borne by caisson over Edmund Pettus Bridge...</p>
           <!-- Contoh dengan route statis -->
            <router-link :to="'/news/1'">
              <button class="text-red-600 hover:text-red-800 font-semibold mt-4">Baca Selengkapnya</button>
            </router-link>

          </article>
        </div>
      </section>

      <div class="flex justify-between items-center">
        <!-- Previous Page Button -->
        <button @click="prevPage" :disabled="currentPage === 1" class="px-4 py-2 text-white bg-red-600 rounded-lg hover:bg-red-700">
          Previous
        </button>

        <!-- Next Page Button -->
        <button @click="nextPage" :disabled="currentPage === totalPages" class="px-4 py-2 text-white bg-red-600 rounded-lg hover:bg-red-700">
          Next
        </button>
      </div>


    </div>
  </div>
  <FooterNews />
</template>

<script>

import FooterNews from '@/components/FooterNews.vue';
import NavbarNews from '@/components/NavbarNews.vue';

export default {
  components: {
    FooterNews,
    NavbarNews
  },
  data() {
    return {
      currentPage: 1,  // Keeps track of the current page
      articlesPerPage: 1, // Limits the number of articles per page
      articles: [        // Sample data for articles
        { id: 1, judul: 'Cake meme reflects coronavirus absurdity...', deskripsi: 'A viral video depicting hyper-realistic cakes...', gambar: '@/assets/bannerberita.jpeg' },
        { id: 2, judul: 'John Lewis makes final journey...', deskripsi: 'The body of the late US Rep. John Lewis...', gambar: '@/assets/bannerberita.jpeg' },
        { id: 3, judul: 'Beloved Arizona coach loses battle...', deskripsi: 'The Arizona coach lost his battle with...', gambar: '@/assets/bannerberita.jpeg' },
        { id: 4, judul: 'New Study on Climate Change...', deskripsi: 'A new study reveals important data...', gambar: '@/assets/bannerberita.jpeg' },
        { id: 5, judul: 'The Impact of Technology on Society...', deskripsi: 'Exploring how technology is changing the world...', gambar: '@/assets/bannerberita.jpeg' },
        { id: 6, judul: 'Global Health Crisis: Solutions Needed', deskripsi: 'Experts discuss how to tackle global health issues...', gambar: '@/assets/bannerberita.jpeg' }
      ]
    };
  },
  computed: {
    totalPages() {
      return Math.ceil(this.articles.length / this.articlesPerPage); // Calculate total pages based on articles
    },
    paginatedArticles() {
      const start = (this.currentPage - 1) * this.articlesPerPage;
      const end = start + this.articlesPerPage;
      return this.articles.slice(start, end); // Return a slice of articles for the current page
    }
  },
  methods: {
    nextPage() {
      if (this.currentPage < this.totalPages) {
        this.currentPage++;
      }
    },
    prevPage() {
      if (this.currentPage > 1) {
        this.currentPage--;
      }
    }
  },
  name: 'NewsPage'
};
</script>
<style scoped>

@media (max-width: 640px){
  .w-full {
    width: 100%;
  }
  .sm\:w-1\/3 {
    width: 100%; /* Stacks the cards vertically on small screens */
  }
}

</style>
