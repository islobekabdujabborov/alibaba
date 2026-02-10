<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <header class="w-[1248px] border-[1px] border-gray-300 rounded-lg p-6 flex justify-between items-center gap-6">
    <div id="ava">
      <img class="rounded-full border-10 border-green" src="/public/image.png" alt="avatar" width="152.31"
        height="152.31">
    </div>
    <div>
      <div class="flex justify-between w-full p-5 translate-x-[-100px]">
        <div>
          <h1 class="text-[30px] font-bold">
            Islombek Abdujabborov
          </h1>
          <p class="text-lg text-[#565563] mt-1">
            Frontend Developer
          </p>
          <p class="text-[#ababab] text-[14px]"><i class="fa-solid fa-location-dot"></i> Andijon, UZB • <i
              class="fa-regular fa-clock"></i>UZT (GMT-5)</p>
        </div>
        <div class="px-[30px]">
          <div class="translate-x-[85px]">
            <button class="bg-[#4b42d9] text-white px-4 py-2 rounded-md mx-[10px] gap-2"><i
                class="fa-regular fa-message"></i> Contact Me</button>
            <button class=" text-black px-4 py-2 rounded-md gap-2 border-[1px] border-gray-300 p-6"><i
                class="fa-solid fa-eye"></i> Resume</button>
          </div>
          <div class="flex gap-3 my-2 justify-end translate-x-[85px]">
          <a class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-100 hover:bg-gray-200 text-gray-700"
            href="#"><i class="fa-brands fa-github"></i></a>
          <a class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-100 hover:bg-gray-200 text-gray-700"
            href="#"><i class="fa-brands fa-twitter"></i></a>
          </div>
        </div>
      </div>
      <div class="w-[960px] mt-10 translate-x-[-60px] translate-y-[-20px]">
        <div class="flex justify-between items-center">
          <h3 class="text-sm font-medium text-gray-700">Profile Completion</h3>
          <h3 class="text-sm font-medium text-[#4b41d9]">85%</h3>
        </div>
        <div class="rounded-full w-[960px] h-[10px] my-3 bg-[#e5e7eb]">
          <div class="rounded-full w-[828px] h-[10px] bg-[#4f46e5]"></div>
        </div>
        <div>
          <p class="text-xs text-gray-500">Complete your profile to increase visibility to potential clients</p>
        </div>
      </div>
    </div>
  </header>
  <div class="w-[1248px] mx-auto mt-[30px]">
    <div class="flex gap-6 w-full">
      <div>
        <div class="w-[394px] bg-white rounded-xl shadow-md border border-gray-100 p-6">
          <h3 class="text-[20px] font-semibold text-gray-800 mb-2">About Me</h3>
          <p class="text-gray-600 mb-4">1 yildan ortiq tajribaga ega, ishtiyoqli va mas’uliyatli veb-dasturchiman.
            Asosan
            foydalanuvchi uchun qulay, zamonaviy va responsiv saytlar yaratishga ixtisoslashganman. Front-end
            yo‘nalishida
            chuqur bilim va tajribaga egaman, shu bilan birga back-end texnologiyalarini ham yaxshi bilaman. Toza va
            samarali kod yozish, shuningdek, har bir mijoz uchun yuqori darajadagi foydalanuvchi tajribasini ta’minlash
            mening asosiy maqsadim.</p>
          <h3 class="text-[18px] font-semibold text-gray-800 mb-2">ko‘nikmalar</h3>
          <div class="flex flex-wrap gap-2 mb-4">
            <span class="text-xs px-3 py-1 rounded-full bg-blue-100 text-blue-800">HTML5</span>
            <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">CSS3</span>
            <span class="text-xs px-3 py-1 rounded-full bg-yellow-100 text-yellow-800">JavaScript</span>
            <span class="text-xs px-3 py-1 rounded-full bg-green-100 text-green-800">Vue.js</span>
            <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Tailwind CSS</span>
          </div>

          <div class="border-t pt-3 text-sm text-gray-700">
            <div class="flex justify-between mb-2">
              <span>Experience</span>
              <span>1+ years</span>
            </div>
            <div class="flex justify-between mb-2">
              <span>Projects Completed</span>
              <span>10</span>
            </div>
            <div class="flex items-center justify-between">
              <div class="flex items-center gap-1 text-yellow-400">
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
              </div>
              <div class="text-sm text-gray-600">4.8/5</div>
            </div>
          </div>
        </div>
        <div class="w-[394px] bg-white rounded-xl mt-[30px] shadow-md border border-gray-100 p-6">
          <h3 class="text-lg font-semibold text-gray-800 mb-2">Activity & Stats</h3>
          <h4 class="text-sm font-medium text-gray-700 mb-3">Contribution Graph</h4>
          <p class="text-xs text-gray-500 mb-4">Last 15 weeks of activity</p>

          <div class="text-sm text-gray-700 mb-4">
            <div class="flex justify-between mb-2"><span>Response Rate</span><span class="font-semibold">95%</span>
            </div>
            <div class="flex justify-between mb-2"><span>Response Time</span><span class="font-semibold">&lt; 2
                hours</span>
            </div>
            <div class="flex justify-between mb-2"><span>On-time Delivery</span><span class="font-semibold">98%</span>
            </div>
          </div>

          <h4 class="text-sm font-medium text-gray-700 mb-3">Recent Activity</h4>
          <ul class="space-y-3 text-sm text-gray-700">
            <li class="flex items-start gap-3">
              <span class="w-3 h-3 mt-1 rounded-full bg-green-500"></span>
              <div>
                <div class="font-medium">Completed project "IT house"</div>
                <div class="text-xs text-gray-500">2 days ago</div>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="w-3 h-3 mt-1 rounded-full bg-blue-500"></span>
              <div>
                <div class="font-medium">Started new project "Financial Dashboard"</div>
                <div class="text-xs text-gray-500">5 days ago</div>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="w-3 h-3 mt-1 rounded-full bg-yellow-500"></span>
              <div>
                <div class="font-medium">Published article "Modern CSS Techniques"</div>
                <div class="text-xs text-gray-500">1 week ago</div>
              </div>
            </li>
            <li class="flex items-start gap-3">
              <span class="w-3 h-3 mt-1 rounded-full bg-purple-500"></span>
              <div>
                <div class="font-medium">Contributed to open-source project "React UI Kit"</div>
                <div class="text-xs text-gray-500">2 weeks ago</div>
              </div>
            </li>
          </ul>
        </div>
        <form class="w-[394px] bg-white rounded-xl mt-[30px] shadow-md border border-gray-100 p-6">
          <h3 class="text-lg font-semibold text-gray-800 mb-2">Contact Me</h3>
          <div class="space-y-4">
            <div class="flex gap-8">
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-1">Full Name*</label>
                <input type="text" placeholder="Islombek Abdujabborov" required=""
                  class="w-[156px] px-3 py-2 border outline-none border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-1">Telegram Username*</label>
                <input type="text" placeholder="Islombek_1111"
                  class="w-[156px] px-3 py-2 border outline-none border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
              </div>
            </div>
            <div>
              <label class="block text-sm font-medium text-gray-700 mb-1">Subject *</label>
              <input type="email" placeholder="Bu murojaat nima bilan bog‘liq"
                class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
            </div>
            <div>
              <label class="block text-sm font-medium text-gray-700 mb-1">Message *</label>
              <textarea rows="4" placeholder="Xabaringizni shu yerga yozing..."
                class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500"></textarea>
            </div>
            <button type="submit"
              class="w-full bg-[#4f46e5] hover:bg-green-600 text-white py-2 px-4 rounded-md transition duration-200">Send
              Message</button>
          </div>
        </form>
      </div>
      <div class="w-[821px] mt-8 bg-white rounded-xl p-6 border border-gray-100">
        <div class="flex items-center justify-between mb-6">
          <h2 class="text-2xl font-semibold text-gray-800">Portfolio</h2>
          <button class="bg-[#5b45f2] text-white px-4 py-2 rounded-full">All Projects</button>
        </div>

        <div class="grid grid-cols-2 gap-6">
          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project1.jpg" alt="project 1" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Fashion E-commerce Platform</h3>
              <p class="text-gray-600 mb-4 text-sm">A full-featured e-commerce website with product catalog, shopping
                cart, and payment integration.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-blue-100 text-blue-800">React</span>
                <span class="text-xs px-3 py-1 rounded-full bg-green-100 text-green-800">Node.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">MongoDB</span>
                <span class="text-xs px-3 py-1 rounded-full bg-purple-100 text-purple-800">Stripe</span>
              </div>
            </div>
          </div>

          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project2.jpg" alt="project 2" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Financial Dashboard</h3>
              <p class="text-gray-600 mb-4 text-sm">Interactive dashboard for financial data visualization and analysis
                with real-time updates.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Vue.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">D3.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-red-100 text-red-800">Firebase</span>
                <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">REST API</span>
              </div>
            </div>
          </div>
          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project2.jpg" alt="project 2" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Financial Dashboard</h3>
              <p class="text-gray-600 mb-4 text-sm">Interactive dashboard for financial data visualization and analysis
                with real-time updates.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Vue.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">D3.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-red-100 text-red-800">Firebase</span>
                <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">REST API</span>
              </div>
            </div>
          </div>
          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project2.jpg" alt="project 2" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Financial Dashboard</h3>
              <p class="text-gray-600 mb-4 text-sm">Interactive dashboard for financial data visualization and analysis
                with real-time updates.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Vue.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">D3.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-red-100 text-red-800">Firebase</span>
                <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">REST API</span>
              </div>
            </div>
          </div>
          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project2.jpg" alt="project 2" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Financial Dashboard</h3>
              <p class="text-gray-600 mb-4 text-sm">Interactive dashboard for financial data visualization and analysis
                with real-time updates.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Vue.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">D3.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-red-100 text-red-800">Firebase</span>
                <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">REST API</span>
              </div>
            </div>
          </div>
          <div class="bg-white rounded-lg border border-gray-100 overflow-hidden">
            <div class="h-44 bg-gray-200">
              <img src="/public/project2.jpg" alt="project 2" class="w-full h-full object-cover">
            </div>
            <div class="p-5">
              <h3 class="text-xl font-semibold mb-2">Financial Dashboard</h3>
              <p class="text-gray-600 mb-4 text-sm">Interactive dashboard for financial data visualization and analysis
                with real-time updates.</p>
              <div class="flex flex-wrap gap-2">
                <span class="text-xs px-3 py-1 rounded-full bg-teal-100 text-teal-800">Vue.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-amber-100 text-amber-800">D3.js</span>
                <span class="text-xs px-3 py-1 rounded-full bg-red-100 text-red-800">Firebase</span>
                <span class="text-xs px-3 py-1 rounded-full bg-gray-100 text-gray-800">REST API</span>
              </div>
            </div>
          </div>
          
        </div>
        <div class="w-[821px] mx-auto py-10">
  <h2 class="text-2xl font-semibold mb-6">Client Testimonials</h2>

  <div class="grid grid-cols-2 gap-6">
    <!-- Card 1 -->
    <div class="bg-white rounded-2xl p-6 shadow-sm">
      <div class="flex items-center gap-4 mb-4">
        <img
          src="https://i.pravatar.cc/80?img=47"
          class="w-12 h-12 rounded-full object-cover"
        />
        <div>
          <h3 class="font-semibold">Emily Richardson</h3>
          <p class="text-sm text-gray-500">
            Marketing Director, TechVision
          </p>
        </div>
      </div>

      <p class="text-gray-600 italic mb-4">
        "Humoyun delivered our e-commerce website ahead of schedule and exceeded
        all our expectations. His attention to detail and problem-solving skills
        made the development process smooth and stress-free."
      </p>

      <div class="flex text-yellow-400">
        ★★★★★
      </div>
    </div>

    <!-- Card 2 -->
    <div class="bg-white rounded-2xl p-6 shadow-sm">
      <div class="flex items-center gap-4 mb-4">
        <img
          src="https://i.pravatar.cc/80?img=12"
          class="w-12 h-12 rounded-full object-cover"
        />
        <div>
          <h3 class="font-semibold">Michael Chen</h3>
          <p class="text-sm text-gray-500">
            Founder, FinTech Solutions
          </p>
        </div>
      </div>

      <p class="text-gray-600 italic mb-4">
        "Working with Humoyun on our financial dashboard was a great experience.
        He quickly understood our complex requirements and delivered a clean,
        intuitive interface."
      </p>

      <div class="flex text-yellow-400">
        ★★★★★
      </div>
    </div>
    <div class="bg-white rounded-2xl p-6 shadow-sm">
      <div class="flex items-center gap-4 mb-4">
        <img
          src="https://i.pravatar.cc/80?img=32"
          class="w-12 h-12 rounded-full object-cover"
        />
        <div>
          <h3 class="font-semibold">Sarah Johnson</h3>
          <p class="text-sm text-gray-500">
            Product Manager, HealthTech Inc.
          </p>
        </div>
      </div>

      <p class="text-gray-600 italic mb-4">
        "Humoyun transformed our outdated website into a modern, responsive
        platform that perfectly represents our brand."
      </p>

      <div class="flex text-yellow-400">
        ★★★★★
      </div>
    </div>
    <div class="bg-white rounded-2xl p-6 shadow-sm">
      <div class="flex items-center gap-4 mb-4">
        <img
          src="https://i.pravatar.cc/80?img=15"
          class="w-12 h-12 rounded-full object-cover"
        />
        <div>
          <h3 class="font-semibold">David Williams</h3>
          <p class="text-sm text-gray-500">
            CEO, Property Connect
          </p>
        </div>
      </div>

      <p class="text-gray-600 italic mb-4">
        "We hired Humoyun to develop our real estate platform, and he delivered a
        feature-rich website that significantly improved user engagement."
      </p>

      <div class="flex text-yellow-400">
        ★★★★★
      </div>
    </div>
  </div>
</div>
      </div>
      
    </div>
    
  </div>
</template>
<style scoped>
:root {
  --primary: #22c55e;
}

header {
  box-shadow: 1px 3px 8px 0px rgba(0, 0, 0, 0.2);
  margin: 50px auto 0;
}

#ava::after {
  content: "Available";
  padding: 4px 12px;
  width: 71px;
  display: block;
  background-color: #22c55e;
  color: white;
  font-size: 12px;
  border-radius: 100px;
  transform: translateX(90px) translateY(-25px);
}
</style>