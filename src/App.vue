<template>
  <div id="app">
      <div class="bg-white">
           
          <div class="container mx-auto flex items-center py-4">
               <nav class="w-2/5">
                  <a href="#" class="text-grey-darker text-sm mr-4 font-semibold pb-6 border-b border-solid border-transparent hover:border-teal-200 hover:text-teal-400"><i class="fa fa-home fa-lg"></i> Accueil</a>
                  <a href="#" class="text-grey-darker text-sm mr-4 font-semibold pb-4 hover:text-teal-400"><i class="fa fa-bolt fa-lg"></i> Notifications</a>
                  <a href="#" class="text-grey-darker text-sm mr-4 font-semibold pb-4 hover:text-teal-400"><i class="fa fa-envelope fa-lg"></i> Messages</a>
               </nav>
               <div class="w-1/5 text-center">
                  <a href="">
                    <i class="fa fa-twitter fa-lg text-blue-400"></i>
                  </a>
               </div>
               <div class="w-2/5 flex justify-end">
                    <div class="mr-4 relative">
                      <input type="text" class="bg-gray-200 h-8 px-4 py-2 text-xs w-48 rounded-full" placeholder="searsh" />
                      <span class="flex items-center absolute  inset-y-0 right-0 mr-3"><i class="fa fa-search text-grey"></i></span>
                    </div>
                    <div class="mr-4">
                       <a href="#">
                           <img src="https://i.pravatar.cc/300" alt="avater" class="w-8 h-8 rounded-full"/>
                       </a>
                    </div>
                    <div>
                      <button class="bg-teal-400 hover:bg-teal-200 text-white font-medium py-1 px-4 rounded-full">
                        tweet
                      </button>
                    </div>
              </div>
          </div>
          <!-- end container --> 
      </div>
      <div class="bg-h h-112 bg-cover"></div>
        <div class="bg-white shadow">
             <div class="container mx-auto flex items-center relative">
                 <div class="w-1/4">
                      <img  src="https://i.pravatar.cc/150?img=#28"  alt="logo"  class="rounded-full h-48 w-48 absolute left-0 top-0 -mt-20"/>
                 </div> 
                 <div class="w-1/2">
                   <ul class="flex justify-center">
                      <li class="text-center py-3 px-4 border-b-2 border-solid border-teal-200">
                        <a href="#" class="text-gray-600 hover:text-gray-900">
                          <div class="text-sm font-bold tracking-tight mb-1 ">tweets</div>
                          <div class="text-lg tracking-tight font-bold text-teal-200">76</div>
                        </a>
                      </li>
                      <li class="text-center py-3 px-4 border-b-2 border-solid ">
                        <a href="#" class="text-gray-600 hover:text-gray-900 hover:no-underline">
                          <div class="text-sm font-bold tracking-tight mb-1 ">tweets</div>
                          <div class="text-lg tracking-tight font-bold text-teal-200">76</div>
                        </a>
                      </li>
                      <li class="text-center py-3 px-4 border-b-2 border-solid ">
                        <a href="#" class="text-gray-600 hover:text-gray-900 hover:no-underline">
                          <div class="text-sm font-bold tracking-tight mb-1 ">tweets</div>
                          <div class="text-lg tracking-tight font-bold text-teal-200">76</div>
                        </a>
                      </li>
                      <li class="text-center py-3 px-4 border-b-2 border-solid ">
                        <a href="#" class="text-gray-600 hover:text-gray-900 hover:no-underline">
                          <div class="text-sm font-bold tracking-tight mb-1 ">tweets</div>
                          <div class="text-lg tracking-tight font-bold text-teal-200">76</div>
                        </a>
                      </li>
                   </ul>
                 </div> 
                 <div class="w-1/4 flex justify-end items-center">
                     <div class="mr-2">
                       <button class="bg-teal-400 hover:bg-teal-200 text-white font-medium py-1 px-4 rounded-full">
                          Following
                       </button>
                     </div>
                     <div>
                        <a href="#" class="text-gray-400">
                           <i class="fa fa-ellipsis-v fa-lg"></i>
                        </a>
                     </div>
                 </div> 
             </div>
        </div>
        <!--end container -->
        <div class="container mx-auto flex mt-4 text-sm leading-normal">
             <div class="w-1/4 pr-6 mr-2 mt-8 mb-4">
                 <div class="ml-8">
                      <h1 class="text-lg"><a href="#" class="text-black-800">Lorem Ipsum</a></h1>
                      <div class="mb-4"><a href="#" class="text-gray-800">@loramopsam</a></div>
                </div>
                 <div class="mb-4">
                     simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the 
                     <a href="#" class="text-teal-400">@Lorem Ipsum</a>
                     it to make a type specimen book. It has survived 
                 </div>
                 <div class="mb-2 text-teal-400">
                      <i class="fa fa-link fa-lg  mr-1"></i>
                      <a href="#">www.loremopsam.com</a>
                 </div>
                 <div class="mb-2 text-teal-400">
                      <i class="fa fa-calendar fa-lg  mr-1"></i>
                      <a href="#">09/06/2019</a>
                 </div>
                 <div class="mb-4">
                      <button class="bg-teal-400 hover:bg-teal-200 text-white font-medium py-1 px-4 rounded-full w-full h-10">
                        tweet to lorem
                      </button>
                 </div>
                 <div class="mb-2 text-gray-600 ">
                      <i class="fa fa-user fa-lg  mr-1"></i>
                      <a href="#" class="text-teal-400">lorem opserm</a>
                 </div>
                 <div class="mb-4 flex">
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
              
                 </div>
                   <div class="mb-4 flex">
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
                       <a href="#" class="mr-1"><img src="https://i.pravatar.cc/300" alt="avater" class="rounded-full h-12 w-12"/></a>
              
                 </div>
                  <div class="mb-2 text-teal-400">
                      <i class="fa fa-picture-o fa-lg  mr-1"></i>
                      <a href="#">photo & vidio</a>
                 </div> 
                 <div class="mb-4 flex">
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                 </div>
                 <div class="mb-4 flex">
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                      <a href="#"><img src="https://i.pravatar.cc/300" class="w-20 h-20 mr-1 mb-1"/></a>
                 </div>

             </div>
             <div class="w-1/2 bg-white mb-4">
                  <div class="p-2 text-lg font-bold border-b border-solid border-grey-light">
                      <a href="#" class="text-black mr-6">Tweets</a>
                      <a href="#" class="mr-6 text-teal-400">Tweets &amp;Replies</a>
                      <a href="#" class="mr-6 text-teal-400">Media</a>
                  </div>
                  <div class="flex border-b border-solid border-grey-400">
                     <div class="w-1/8 text-right pl-3 pt-3 mb-2">
                        <div><i class="fa fa-thumb-tack text-gray-600 mr-2"></i></div>
                        <div>
                          <a href="#">
                            <img src="https://i.pravatar.cc/500" alt="avater" class=" rounded-full h-12 w-12 mr-2"/>
                          </a>
                        </div>
                     </div>
                     <div class="w-7/8 p-3 pl-0">
                        <div class="text-xs text-gray-600">
                            first tweet
                        </div>
                        <div class="flex justify-between">
                              <div>
                                  <span class="font-bold mr-2">
                                    <a href="#">lorem</a>
                                  </span>
                                  <span class="text-gray-600">
                                    <a href="#">2day</a>
                                  </span>   

                              </div>
                              
                        </div>
                        <div>
                           <img src="https://i.pravatar.cc/500" alt="avater" class="mt-4" />
                        </div>
                        <div class="pb-2 mt-2">
                            <span class="mr-8">
                               <a href="#" class="text-gray-600">
                                  <i class="fa fa-comment fa-lg mr-2"></i> 
                               </a>
                            </span>
                            <span class="mr-8">
                               <a href="#" class="text-gray-600">
                                  <i class="fa fa-retweet fa-lg mr-2"></i> 
                               </a>
                            </span>
                            <span class="mr-8">
                               <a href="#" class="text-gray-600">
                                  <i class="fa fa-heart fa-lg mr-2"></i> 
                               </a>
                            </span>
                             <span class="mr-8">
                               <a href="#" class="text-gray-600">
                                  <i class="fa fa-envelope-o fa-lg mr-2"></i> 
                               </a>
                            </span>
                        </div>
                     </div>
                  </div>
             </div>
             <div class="w-1/4 pl-4">
                  <div class="bg-white p-3 mb-3">
                        <div>
                            <span class="text-lg font-bold">who to follow</span>
                            <span>&middot;</span>
                            <span>
                                <a href="#" class="text-xs"> refresh</a>
                            </span>
                             <span>
                                <a href="#" class="text-xs"> refresh</a>
                            </span>
                        </div>
                  </div>
             </div>
        </div>

  </div>
</template>

<script>
import './assets/main.css'

export default {
  name: 'app',
  
}
</script>

<style>

</style>
