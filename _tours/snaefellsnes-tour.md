---
layout: tour
title: Scenic Snæfellsnes Bus Tour
intro: An introduction some of the best attractions on Snæfellsnes
duration: 5 hours
image: /assets/images/tours/snæfellsnes-tour/businkirkjufell.jpg
order: 20
published: true
cancellation: true
short_description: Explore the best of Snæfellsnes on our popular bus tour
practical_info:
  Price: |
        18.000 ISK per person for adults

        14.500 ISK per person for children (6-15)
  Minimum Age: 6 years old
  Departure Location: Grundarfjörður Harbour, to the right of where you disembark from your ship/tender
  Drop-off Location: Grundarfjörður Harbour
  Duration: 5 hours
  Inclusions: |
        English-speaking Tour Guide 
        
        Entrance Fee to the Maritime Museum in Hellissandur
        
        Free Wi-Fi on the bus
  Group Size: Up to 49 people on the bus
  Distance Driven: 145 km/ 90 mi
bokun_id: 833852
---
<div class="tour-info">
  <div class="info-block">
    <p class="info-title">Tour Highlights</p>
    <ul class="highlights">
      <li>Kirkjufell mountain & waterfalls</li>
      <li>Snæfellsjökull glacier & volcanic landscapes</li>
      <li>Arnarstapi</li>
      <li>Snæfellsjökull National Park Visitor Center</li>
    </ul>
  </div>

  <div class="info-block">
    <p class="info-title">Perfect for Cruise Passengers</p>
    <ul class="highlights">
      <li>Guaranteed return before ship departure</li>
      <li>Full refund if your ship cannot dock</li>
      <li>Pickup at Grundarfjörður harbor</li>
      <li>Tours timed with your ship schedule</li>
    </ul>
  </div>
</div>
---

Ready to explore one of Iceland’s most incredible regions? Join us on a fun and unforgettable **Snæfellsnes Peninsula** shore excursion from **Grundarfjörður** — perfect for cruise ship passengers who want to make the most of their time in Iceland.

Often called “Iceland in Miniature”, the Snæfellsnes Peninsula packs everything you love about Iceland into one amazing region: waterfalls, volcanoes, lava fields, black beaches, dramatic cliffs, and charming fishing villages.

The best part? We pick you up right at the Grundarfjörður **cruise port** — no long transfers, no stress, just straight into the adventure.

We begin our journey along the dramatic coastline to **Malarrif**, where you’ll experience the raw power of the Atlantic Ocean and sweeping views toward the mystical **Snæfellsjökull glacier** — a volcano topped with ice and surrounded by legend. From here you can also enjoy a scenic view of **Lóndrangar** lava stacks. 

Next, we continue to **Arnarstapi**, one of the most beautiful coastal spots in Iceland. Here you can walk along stunning basalt cliffs, spot seabirds, and watch waves crash against natural rock formations and sea arches.

We then visit the **Maritime Museum** in **Hellissandur**, a charming stop that offers a glimpse into Iceland’s fishing heritage and coastal life.

Our final highlight is the iconic **Kirkjufell**, one of the most famous and photographed mountains in Iceland (and yes, it really is that beautiful in real life), along with the nearby waterfalls that complete the picture-perfect view.

From Kirkjufell, we return comfortably by bus to Grundarfjörður harbour. If you’re feeling up for a bit of fresh air, you can choose to walk back to the Grundarfjörður harbour — a scenic route of approximately 2 km (1.2 miles), which takes around 30 minutes at a relaxed pace.

Along the way, expect plenty of photo stops, fresh air, and stories from our guides who love sharing Iceland’s history, folklore, and hidden gems. This isn’t just a tour — it’s a fun, relaxed experience designed to give you the real Iceland.

If you are looking for a shorter version of this tour, you can check out our **[Snæfellsnes Short Tour]({% link _tours/snaefellsnes-short.md %})**. 

For any questions, do not hesitate to [get in touch](https://rutuferdir.is/#contact). 

<h3>Photo Gallery</h3>

<div class="tour-gallery">
  <img src="/assets/images/tours/snæfellsnes-tour/londrangar.jpg" alt="Londrangar lava plugs" onclick="openLightbox(0)">
  <img src="/assets/images/tours/snæfellsnes-tour/arnarstapi.jpg" alt="Arnarstapi cliffs" onclick="openLightbox(1)">
  <img src="/assets/images/tours/snæfellsnes-tour/maritime-museum.jpg" alt="Hellissandur museum" onclick="openLightbox(2)">
  <img src="/assets/images/tours/snæfellsnes-tour/kirkjufell.jpg" alt="Kirkjufell mountain" onclick="openLightbox(3)">
</div>

<!-- Lightbox -->
<div id="lightbox" onclick="closeLightbox(event)">
  <span class="arrow left" onclick="prevImage(event)">&#10094;</span>
  <img id="lightbox-img" src="" alt="" onclick="event.stopPropagation()">
  <span class="arrow right" onclick="nextImage(event)">&#10095;</span>
</div>

<script>
  const galleryImages = [
    "/assets/images/tours/snæfellsnes-tour/londrangar.jpg",
    "/assets/images/tours/snæfellsnes-tour/arnarstapi.jpg",
    "/assets/images/tours/snæfellsnes-tour/maritime-museum.jpg",
    "/assets/images/tours/snæfellsnes-tour/kirkjufell.jpg"
  ];

  let currentIndex = 0;

  function openLightbox(index) {
    currentIndex = index;
    document.getElementById("lightbox-img").src = galleryImages[currentIndex];
    document.getElementById("lightbox").style.display = "flex";
  }

  function closeLightbox(event) {
    if (!event || event.target.id === "lightbox" || event.target.classList.contains("close")) {
      document.getElementById("lightbox").style.display = "none";
    }
  }

  function nextImage(event) {
    event.stopPropagation();
    currentIndex = (currentIndex + 1) % galleryImages.length;
    document.getElementById("lightbox-img").src = galleryImages[currentIndex];
  }

  function prevImage(event) {
    event.stopPropagation();
    currentIndex = (currentIndex - 1 + galleryImages.length) % galleryImages.length;
    document.getElementById("lightbox-img").src = galleryImages[currentIndex];
  }

  document.addEventListener("keydown", function(e) {
    if (e.key === "Escape") {
      document.getElementById("lightbox").style.display = "none";
    }
  });
</script>

---

<h4>Food & Refreshments</h4>

We take a longer break in Arnarstapi where you can grab food and drinks. It’s a small village, so options are limited and can get busy in the summer — bringing a snack is always a good idea!