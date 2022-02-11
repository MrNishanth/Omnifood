# Omnifood
HTML

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="stylesheet" href="css/media.css" />
    <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script>
    <title>Omnifood</title>
  </head>
  <body>
    <header class="header">
      <a href="#">
      <img class="logo" alt="Omnifood-logo" src="img/omnifood-logo.png" />
      </a>
      <nav class="main-nav">
        <ul class="main-nav-list">
          <li><a class="main-nav-link" href="#">Section 1</a></li>
          <li><a class="main-nav-link" href="#">Section 2</a></li>
          <li><a class="main-nav-link" href="#">Section 3</a></li>
          <li><a class="main-nav-link" href="#">Section 4</a></li>
          <li>
            <a class="main-nav-link nav-cta" href="#">Section 5</a>
          </li>
        </ul>
      </nav>
    </header>
      <section class="section-hero">
        <div class="hero">
          <div class="hero-txt-box">
            <h1 class="primary-heading">
              A healthy meal delivered to your door, every single day
            </h1>
            <p class="hero-description">
              The smart 365-days-per-year food subscription that will make you
              eat healthy again. Tailored to your personal tastes and
              nutritional needs.
            </p>
            <a href="#" class="btn btn--cta margin-right-sm"
              >Start Eating Well</a
            >
            <a href="#" class="btn btn--outline">Learn more &darr;</a>
            <div class="Delivered-meals">
              <div class="Delivered-imgs">
                <img src="img/customers/customer-1.jpg" alt="customer-photo" />
                <img src="img/customers/customer-2.jpg" alt="customer-photo" />
                <img src="img/customers/customer-3.jpg" alt="customer-photo" />
                <img src="img/customers/customer-4.jpg" alt="customer-photo" />
                <img src="img/customers/customer-5.jpg" alt="customer-photo" />
              </div>
              <p class="Delivered-text">
                <span>250,000+</span> meals delivered last year!
              </p>
            </div>
          </div>
          <div class="hero-img-box">
            <img
              src="img/hero.png"
              class="hero-img"
              alt="woman enjoying food"
            />
          </div>
        </div>
      </section>

      <section class="featured-section">
       <div class="container">
         <h2 class="featuredin-heading">As featured in</h2>
         <div class="logos">
         <img src="img/logos/techcrunch.png" alt="techcrunch logo" />
         <img src="img/logos/business-insider.png" alt="business-insider logo" />
         <img src="img/logos/forbes.png" alt="forbes logo" />
         <img src="img/logos/the-new-york-times.png" alt="the-new-york-times logo" />
         <img src="img/logos/usa-today.png" alt="usa-today logo" />
         </div>
       </div>
     </section>

      <section class="section-how">
        <div class="container">
          <span class="subheading">How it works</span>
          <h2 class="Secondary-heading">
            Your daily dose of health in 3 simple steps
          </h2>
        </div>

        <div class="container grid grid--2-cols grid--center-v">
          <!-- step 1 -->
          <div class="step-text">
            <p class="step-number">01</p>
            <h3 class="tertiary-heading">
              Tell us what you like (and what not)
            </h3>
            <p class="step-description">
              Never again waste time thinking about what to eat! Omnifood AI
              will create a 100% personalized weekly meal plan just for you. It
              makes sure you get all the nutrients and vitamins you need, no
              matter what diet you follow!
            </p>
          </div>
          <div class="step-img-box">
            <img
              src="img/app/app-screen-1.png"
              class="step-img"
              alt="iphone screening"
            />
          </div>

            <!-- step 2 -->

            <div class="step-img-box">
              <img
                src="img/app/app-screen-2.png"
                class="step-img"
                alt="iphone screening"
              />
            </div>
            <div class="step-text">
              <p class="step-number">02</p>
              <h3 class="tertiary-heading">Approve your weekly meal plan:</h3>
              <p class="step-description">
                Approve your weekly meal plan: Once per week, approve the meal
                plan generated for you by Omnifood AI. You can change
                ingredients, swap entire meals, or even add your own recipes.
              </p>
            </div>

            <!-- step 3 -->
            <div class="step-text">
              <p class="step-number">03</p>
               <h3 class="tertiary-heading">Receive meals at convenient time:</h3>
              <p class="step-description">
               Best chefs in town will cook your selected meal every day, and we will deliver it to your door whenever works best for you. You can change delivery schedule and address daily!
              </p>
            </div>
        
          <div class="step-img-box">
            <img
              src="img/app/app-screen-3.png"
              class="step-img"
              alt="iphone screening"
            />
           
          </div>
        </div>
      </div>
      </section>

      <section class="section-meals">
        <div class="container center-text">
          <span class="subheading">Meals</span>
          <h2 class="Secondary-heading">
            Omnifood AI chooses from 5,000+ recipes
          </h2>
        </div>
        <div class="container grid grid--3-cols">
          <div class="meals">
            <div class="meal-tag">
            <img class="meal-img" src="img/meals/meal-1.jpg" alt="Japanese Gyozas" />
           </div>
           <div class="meal-content">
            <span class="tag tag--vegetarian">Vegetarian</span>
            <p class="meal-title">Japanese Gyozas</p>
            <ul class="meal-attributes">
              <li class="meal-attribute"><ion-icon class="meal-icon" name="flame"></ion-icon><span><strong>750</strong> calories</span></li>
              <li class="meal-attribute"><ion-icon class="meal-icon" name="restaurant"></ion-icon><span>Nutriscore &reg; <strong>74</strong></span></li>
              <li class="meal-attribute"><ion-icon class="meal-icon" name="star"></ion-icon><span><strong>4.9</strong> Rating (665)</span></li>
            </ul>
          </div>
          </div>

          <div class="meals">
            <div class="meal-tag">
            <img class="meal-img" src="img/meals/meal-2.jpg" alt=" Avocado Salad" />
           </div>
           <div class="meal-content">
            <span class="tag tag--vegan">Vegan</span>
            <span class="tag tag--paleo">paleo</span>
            <p class="meal-title"> Avocado Salad</p>
            <ul class="meal-attributes">
              <li class="meal-attribute"><ion-icon class="meal-icon" name="flame"></ion-icon><span><strong>400</strong> calories</span></li>
              <li class="meal-attribute"><ion-icon class="meal-icon" name="restaurant"></ion-icon><span>Nutriscore &reg; <strong>92</strong></span></li>
              <li class="meal-attribute"><ion-icon class="meal-icon" name="star"></ion-icon><span><strong>4.8</strong> Rating (445)</span></li>
            </ul>
          </div>
          </div>
          
          <div class="diets">
            <h3 class="tertiary-heading">works with any diet:</h3>
            <ul class="list">
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Vegetarian</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Vegan</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Pescatarian</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Gluten-free</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Lactose-free</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Keto</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Paleo</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Low FODMAP</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Kid-friendly</span></li>
          </div>
        </div>
       </section>

       <section class="section-testimonials">
        <div class="testimonials-container">
          <span class="subheading">Testimonials</span>
          <h2 class="Secondary-heading">
            Once you try it, you can't go back
          </h2>
        
         <div class="testimonials">
           <figure class="testimonial">
             <img class="testimonial-img" src="img/customers/dave.jpg" alt="testimonial of dave"/>
             <blockquote class="testimonial-text">Inexpensive, healthy and great-tasting meals, without even having to order manually! It feels truly magical.</blockquote>
             <p class="testimonial-name">&mdash; Dave Bryson</p>
           </figure> 

           <figure class="testimonial">
            <img class="testimonial-img" src="img/customers/ben.jpg" alt="testimonial of Ben Hadley" />
            <blockquote class="testimonial-text">The AI algorithm is crazy good, it chooses the right meals for me every time. It's amazing not to worry about food anymore!</blockquote>
            <p class="testimonial-name">&mdash; Ben Hadley</p>
          </figure> 

          <figure class="testimonial">
            <img class="testimonial-img" src="img/customers/steve.jpg" alt="testimonial of Steve Miller" />
            <blockquote class="testimonial-text">Omnifood is a life saver! I just started a company, so there's no time for cooking. I couldn't live without my daily meals now!</blockquote>
            <p class="testimonial-name">&mdash; Steve Miller</p>
          </figure> 

          <figure class="testimonial">
            <img class="testimonial-img" src="img/customers/hannah.jpg" alt="testimonial of Hannah Smith" />
            <blockquote class="testimonial-text">I got Omnifood for the whole family, and it frees up so much time! Plus, everything is organic and vegan and without plastic.</blockquote>
            <p class="testimonial-name">&mdash; Hannah Smith</p>
          </figure> 
         </div>
        </div>
         <div class="Gallery">
           <figure class="gallery-items">
             <img src="img/gallery/gallery-1.jpg" alt="beautifully arranged foods" />
           </figure>
           <figure class="gallery-items">
            <img src="img/gallery/gallery-2.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-3.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-4.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-5.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-6.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-7.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-8.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-9.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-10.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-11.jpg" alt="beautifully arranged foods" />
          </figure>
          <figure class="gallery-items">
            <img src="img/gallery/gallery-12.jpg" alt="beautifully arranged foods" />
          </figure>
         </div>
        </section>
      <section class="section-pricing">
        <div class="container">
          <span class="subheading">Pricing</span>
          <h2 class="Secondary-heading">
            Eat Well without breaking the bank
          </h2>
        </div>
        
        <div class="container grid grid--2-cols">
          <div class="pricing-plan  pricing-plan--starter">
            <header class="plan-header">
            <p class="plan-name">Starter</p>
            <p class="plan-price"><span>$</span>300</p>
            <p class="plan-text">just 13$ per meal/day!</p>
          </header>
            <ul class="list">
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span> 1 meal per day</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Order between 11am and 9pm</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Free Delivery</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="close-circle"></ion-icon><span></span></li>
              </ul>
              <div class="sign-up-btn">
              <a href="#" class="btn btn--cta"
              >Start Eating Well</a
            >
            </div>
            </div>
            <div class="pricing-plan pricing-plan--complete">
              <header class="plan-header">
              <p class="plan-name">complete</p>
            <p class="plan-price"><span>$</span>649</p>
            <p class="plan-text">just 11$ per meal/day!</p>
          </header>
            <ul class="list">
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span><strong>2 meals</strong> per day</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Order <strong>24/7</strong></span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Free Delivery</span></li>
              <li class="list-items"><ion-icon class="list-icon" name="checkmark-circle"></ion-icon><span>Get access to latest recipes</span></li>
              </ul>
              <div class="sign-up-btn">
              <a href="#" class="btn btn--cta"
              >Start Eating Well</a>
            </div>
            </div>
          </div>
         <div class="container grid grid--4-cols">
           <div class="feature"> 
            <ion-icon class="feature-icon" name="infinite"></ion-icon>
             <p class="feature-title">Never cook again!</p>
             <p class="feature-text">Our subscriptions cover 365 days per year, even including major holidays.</p>
           </div>
           <div class="feature"> 
            <ion-icon class="feature-icon" name="nutrition"></ion-icon>
             <p class="feature-title">Local and organic</p>
             <p class="feature-text">Our cooks only use local, fresh, and organic products to prepare your meals.</p>
           </div>
           <div class="feature"> 
            <ion-icon class="feature-icon" name="leaf"></ion-icon>
             <p class="feature-title">No waste</p>
             <p class="feature-text"> All our partners only use reusable containers to package all your meals.</p>
           </div>
           <div class="feature"> 
            <ion-icon class="feature-icon" name="pause"></ion-icon>
             <p class="feature-title">Pause anytime</p>
             <p class="feature-text"> Going on vacation? Just pause your subscription, and we refund unused days.
            </p>
           </div>
         </div>
      </section>

      <section class="section-cta" action="#">
        <div class="container">
          <div class="cta">
          <div class="cta-text-box">
            <h2 class="Secondary-heading">Get your first meal for Free</h2>
            <p class="cta-text">Healthy, tasty and hassle-free meals are waiting for you. Start eating well today. You can cancel or pause anytime. And the first meal is on us!</p>

            <form class="cta-form">
              <div>
              <label for="Full-Name">Full Name</label>
              <input id="Full-Name" type="text" placeholder="Arun Nishanth" required />
              </div>

              <div>
              <label for="Email">Email</label>
              <input id="Email" type="email" placeholder="arun@example.com" required />
            </div>


            <div>
              <label for="select-where">Where did you hear from us</label>
              <select id="select-where" required>
                <option value="">Select one</option>
                <option value="Freinds">Friends & Family</option>
                <option value="youtube">Youtube video</option>
                <option value="ad">Facebook ad</option>
                <option value="others">others</option>
              </select>
            </div>

              <button class="btn btn--form">Sign Up</button>
            </form>
          </div>
            <div class="cta-image" role="img" aria-label="women enjoying food"></div>
          </div>
        </div>
      </section>
      </main>
     <footer class="footer">
       <p>Copyrights &copy; 2022 All rights reserved</p>
     </footer>
     
  </body>
</html>

