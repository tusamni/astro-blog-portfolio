---
# imports
setup: |
  import Layout from "@/layouts/ShootLayout"
  import Image from "@/components/image/Image"
  import Gallery from "@/components/image/Gallery"

# meta
tags:
  - porsche
  - 911s
  - dripping springs
  - turbo
category: bring a trailer
date: 2019-08-17

# content
title: Signal Yellow 1973 911S Targa
description: A gorgeous 911S Targa I shot for a future auction on Bring a Trailer.

# photos
hero: /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_001.jpg
gallery01:
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_001.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_002.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_003.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_004.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_005.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_006.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_007.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_008.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_009.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_010.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_011.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_012.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_013.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_014.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_015.jpg
  - /shoots/2019/2019-08-17-signal-yellow-911/911s-targa_016.jpg
---

A friend decided to list this gorgeous 911S Targa. It was a car owned by a well known member of the early Porsche community who sadly passed away. My friend was able to purchase this car from his estate with the intention on finishing the car to the standars of the previous owner.

What's not to love about this car: Pepita houndstooth and tan leather interior, targa, "S" and finished in Signal Yellow from the factory. It's an amazing assortment of options, one of my favorite cars in his collection.

This car has yet to make it to Bring a Trailer though. It's still at the shop receiving the final touches. When it does get listed, it's going to the moon.

<div class="gallery">
    {frontmatter.gallery01.map(i =>
        <Gallery file={i}>
            <Image
                file={i}
                sizes="(min-width: 1024px) 800px, 100vw"
            />
        </Gallery>
    )}
</div>
