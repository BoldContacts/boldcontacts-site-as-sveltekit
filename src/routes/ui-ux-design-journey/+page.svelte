<div class="max-w-2xl m-auto">

<img src="/assets/screenshot.png" alt="Screenshot gallery of BoldContacts on an iPhone" loading="lazy">
    
<h1>UI/UX design journey</h1>
    
<p>BoldContacts has a UI/UX design journey that emphasizes the user's needs.</p>

<p>The UI/UX design journey started when my mom (mother-in-law) was diagnosed with Alzheimer's Disease, and my dad (stepfather) was diagnosed with Parkinson's Disease. Both parents loved their iPhones, and used them often for contacting friends and relatives via phone calls and FaceTime.</p>


<h2>iPhone Contacts app</h2>

<p>The default iPhone Contacts app list page looks like this:</p>

<p><img src="/assets/ui-ux-design-journey/apple-ios-contacts-list@460x996.png" width="50%" alt="Screenshot of Apple iPhone Contacts app with list view" loading="lazy"></p>


<h2>iPhone Contacts app issues</h2>

<p>Unfortunately, Alheimer's Disease, Parkinson's Disease, and Age-Related Macular Degeneration (AMD) often cause impairments making it hard to use the default iPhone Contacts app:</p>

<ul>

    <li>Alzheimer's Disease often causes cognitive impairment, including memory issues. My mom started having trouble remembering how to unlock her iPhone, how to launch the default iPhone Contacts app, and how to connect via phone or FaceTime.</li>

    <li>Parkinson's Disease often causes motor impairment, including hand tremors. My dad started having trouble using the iPhone icons, how to navigate the default iPhone Contacts app, and how to accurately tap the contact item to dial.</li>

    <li>Age-Related Macular Degeneration often causes vision impairment, including blurred vision and less than 20/20 vision. My folks started having a hard time seeing the iPhone text, even with Apple's accessbility font scaling turned up.</li>

</ul>

<p>As their diseases progressed, they lost their ability to use the default iPhone Contacts app. This loss cut them off from their video calling. This made them sad, lonely, and more confused.</p>


<h2>Attempt 1: Look for accessibility apps</h2>

<p>I looked through many Apple App Store apps, to try to find any easier way of making phone calls and video calls. I found a bunch of potential alternative phone dialer apps and evaluated them.</p>

<ul>
    
    <li>Many of the apps provided more information on each screen, such as for salespeople making many business calls. These apps wouldn't work for my folks.</li>

    <li>A few of the apps did provide easier ways to call, but had problems such as recent negative reviews, or a lack of maintenance, or a requirement for buying a new iPhone to run the newest iOS.</li>

    <li>Key learning: Bold big buttons help, and are significantly easier to see and tap than Apple's default buttons.</li>

</ul>

<p>After much searching, I concluded that there wasn't a viable app.</p>


<h2>Attempt 2: Voice control ~ Amazon Echo Dot</h2>

<p>Because of the dementia, and hand tremors, and macular degeneration, my next attempt was to try voice control, using the Amazon Echo Dot:</p>

<p><img src="/assets/ui-ux-design-journey/amazon-echo-dot@960x563.jpg" width="50%" alt="Amazon Echo Dot product photo" loading="lazy"></p>

<p>Unfortunately, my folks weren't able to understand voice control.</p>

<ul>
    
    <li>My mom had never used voice control before, and didn't understand the overall concept of talking to the room.</li>

    <li>My dad had used Amazon Alexa for years at home, especially for playing music. But he lost the ability to remember how to trigger the Echo.</li>

    <li>Key learning: a physical device with touch is easier to understand than room-wide voice control.</li>

</ul>

<p>After many tries, I concluded that voice control was too confusing for my folks. At the same time, I saw them both able to reliably dial their land-line push-button phones. So I searched for a physical solution.</p>


<h2>Attempt 3: Dedicated device ~ Facebook Portal</h2>

<p>Because my folks were still able to use their physical phones, I searched for a physical device that worked more like a desktop phone. After talking with many of my friends, including friends from Facebook, I found the Facebook Portal:</p>

<p><!-- img src="/assets/ui-ux-design-journey/facebook-portal-10-inch@960x782.png" width="50%" alt="Facebook Portal 10-inch product photo" loading="lazy" --></p>

<p>Unfortunately, the Facebook Portal is quite confusing, even to me.</p>

<ul>
    
    <li>I tried the setup process for more than hour, and hit many UI/UX glitches and one severe bug. Even once I succeeded, the Portal tried to do much more than they needed.</li>

    <li>Because of the physical weight and shape, the Facebook Portal wasn't easy to carry around, nor put in a purse, nor mount to a wheelchair.</li>

    <li>Key learnings: the folks preferred the larger screen size of the Portal 10" over the smaller screen size of the iPhone, and also sometimes liked using the desktop stand capabily.</li>

</ul>

<p>After a week, I returned the Facebook Portal. In my opinion, the Portal is a great concept, but with too many UI/UX problems. I'll be surprised if Facebook continues to sell it.</p>


<h2>Attempt 4: Dedicated demographic ~ Grandpad</h2>

<p>Because the core problem is that my folks are elderly, next I searched for an elderly-specific solution. Eventually found the Grandpad, which provides a dedicated tablet, with a dedicated mobile connection, and elderly-specific software:</p>

<p><!-- img src="/assets/ui-ux-design-journey/grandpad@960x700.png" width="50%" alt="Grandpad product photo" loading="lazy" --></p>

<p>The Grandpad works well, and the team is highly helpful. Unfortunately, it fell short for my folks' specific needs:</p>

<ul>
    
    <li>The Grandpad comes with its own mobile phone service, which has a significant monthly cost.</li>

    <li>The Grandpad was confusing to my folks' caregivers, because they'd never seen one.</li>

    <li>Key learnings: to be adopted by caregivers, it's a must to use commodity devices (iPhones, iPads, etc.) and free WiFi.</li>
</ul>

<p>The Grandpad was close, but not quite. What I learned is that a great solution needs to be able to use free WiFi, rather than requiring a mobile phone montly payment. And a great solution needs to be something very easy for caregivers to understand and use.</p>


<h2>BoldContacts sketches</h2>

<p>I started the BoldContacts sketches informed by the default iPhone Contacts app person page, which looks like this:</p>
    
<p><img src="/assets/ui-ux-design-journey/apple-ios-contacts-page@460x996.png"  width="45%" alt="Screenshot of Apple iPhone Contacts app with page view" loading="lazy"></p>

<p>The page has quick wins:</p>

<ul>

    <li>Drop unnecessary information, such as the postal address map section, email address section, birthday section, etc.</li>

    <li>Excise duplicity, such as the page showing a FaceTime icon near the top, plus the "FaceTime" area.</li>

    <li>Runs on any typical off-the-shelf iPhone and iPad. These match what caregivers know and use.</li>

    <li>Drop action links with labels "Send Message" and "Share Contact", etc., because they're not necessary, and because most of the target users don't understand that those action links are equivalent to buttons.</li>

</ul>


<h2>BoldContacts functionality</h2>

<p>Thanks to all the attempts, I had a good idea of what a solution needed:</p>

<ul>

    <li>Bold big text that is especially easy to see. These assist with eyesight problems.</li>

    <li>Bold big buttons that are especially easy to tap. These assist with hand tremor problems.</li>

    <li>Runs on any typical off-the-shelf iPhone and iPad. These match what caregivers know and use.</li>

    <li>Works with existing free WiFi, rather than requiring sign up for a new cellular contract.</li>

</ul>


<h2>Iterations for users</h2>

I started coding and iterating with users and caregivers, and learned more about the user needs:

<ul>

    <li>The number of important contacts is small, typically 9 people or fewer. The important contacts were family members, closests friends, and some healthcare providers.</li>

    <li>The app must be free, because any kind of payment is too complex for the user.</li>

    <li>For some users, the device needs extra protection, such as a drop-proof spill-proof case.</li>

    <li>Caregivers strongly want options for form factors, such as an option for a tabletop stand, an option for a wall mount akin to a picture frame, and an option for a wheelchair attachment.</li>

</ul>


<h2>Iterations for Apple iOS</h2>

I learned more about Apple iOS, the Swift programming language, and the SwiftUI framework:

<ul>

    <li>Some of the typical Apple mobile UI/UX interactions do not work well for many users, especially invisible interactions. For example, press-drag-scroll is used in the Contacts app for scrolling up and down through the contacts list; this was confusion, and worse, did not function reliably when the user had hand tremors.</li>

    <li>Some of the Apple security restrictions make it hard to use a cloud-based database, but easy to use the user's existing iOS contacts databse.</li>

    <li>Some of the current Apple iOS coding practices won't run on older equiment, such as a six-year-old iPhone or iPad, which cannot run the current iOS. But many of the users have these older deveices, and cannot afford to buy a new iPhone, or cannot figure out how to set up a new iPhone.</li>

    <li>Many older devices are cheap and easy to procure. In fact, many users had family members who had an older iPhone or iPad that wasn't being used, and could be transferred to the user.</li>

</ul>


<h2>Simpler is better</h2>

I iterated more and learned in many cases, very simple UI/UX tends to works better for the users:

<ul>

    <li>Use one page for the whole app, rather than multiple pages such as a contacts list page plus a contact person page.</li>

    <li>Spread all the buttons far apart, to make it easier for the user to tap the one they want.</li>

    <li>Display the photo as large as possible, because this helps many users identify the person better/faster, and also provides a feeling of delight.</li>

    <li>Interface elements based on black and white tend to be easier to learn than interface elements based on colors, gradients, grays, and the like.</li>

    <li>Alphabetic sort by first name is easier to understand than alphabetic sort by last name.</li>

    <li>Each contact typically has one preferred contact method, such as always via a phone call, or always via FaceTime, or always via.</li>

    <li>Some users have a very strong preference for their native language. And the number of native langauges is very high. Therefore, internationalization and localization are very important.</li>

</ul>


<h2>Success!</h2>

<p>The result of all the attempts, research, iteration, and testing, is BoldContacts version 1:</p>

<p><img src="/assets/ui-ux-design-journey/boldcontacts-alice@460x996.png" width="50%"  alt="Screenshot of BoldContacts app with page view" loading="lazy"></p>

<p>The total UI/UX design journey took approximately three months:</p>

<ul>

    <li>Much of the time was iterating with users and caregivers.</li>

    <li>Because we found so many kinds of impairments, and so many needs for caregiver options, we believe that customization is important. Therefore we're making BoldContacts free open source, so any developer can use it, change it, and share improvements with everyone.</li>

    <li>Much of the learning is on the roadmap for BoldContacts version 2. Notable new capabilties will include simpler onboarding, an Android version, and a training video for caregivers.</li>

</ul>

</div>