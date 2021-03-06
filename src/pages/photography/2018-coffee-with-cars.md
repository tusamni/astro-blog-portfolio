---
# imports
setup: |
  import Layout from "@/layouts/ShootLayout"
  import Image from "@/components/image/Image"
  import Gallery from "@/components/image/Gallery"

# meta
tags:
  - coffee with cars
  - dripping springs
  - greater goods coffee
category: car show
date: 2018-08-26

# content
title: Coffee With Cars August 2019
description: After picking up a Sony 24-105mm lens, I head to Coffee With Cars.

# photos
hero: /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_002.jpg
gallery01:
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_001.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_002.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_003.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_004.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_005.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_006.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_007.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_008.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_009.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_010.jpg
  - /shoots/2018/2018-08-26-coffee-with-cars/coffee-with-cars-2018_011.jpg
---

After shooting my first Bring a Trailer auction, I figured I needed to get out and shoot more cars. Luckily [Coffee With Cars](https://www.facebook.com/CoffeeWithCars/) happens during the warmer months and it's not far from my house.

## Demon in the Details

There were plenty of interesting cars there, but this was right around the time of the Demon release. I was just blown away with how ridiculous this car was. I can't even imagine trying to put down 800hp on the street, even with road legal slicks.

The demon really is in all the details. It's a single purpose car and Dodge makes no bones about it. I'm in love.

<div class="gallery">
    {frontmatter.gallery01.map((i, index) =>
        <Gallery file={i}>
            <Image
                file={i}
                sizes="(min-width: 1024px) 800px, 100vw"
            />
        </Gallery>
    )}
</div>
