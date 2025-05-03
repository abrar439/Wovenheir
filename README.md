import React from "react"; import { Button } from "@/components/ui/button"; import { Card, CardContent } from "@/components/ui/card";

export default function Home() { return ( <main className="min-h-screen bg-black text-white p-6"> <section className="text-center py-20"> <h1 className="text-5xl font-bold mb-4">Wovenheir</h1> <p className="text-lg max-w-xl mx-auto">Premium streetwear & apparel for the bold generation. Crafted with style, powered by attitude.</p> <Button className="mt-6 text-lg px-6 py-3">Shop Now</Button> </section>

<section className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 py-10">
    <Card>
      <CardContent className="bg-white text-black rounded-2xl p-4">
        <img src="/images/tshirt.png" alt="T-shirt" className="w-full h-56 object-cover rounded-xl" />
        <h2 className="mt-4 text-xl font-semibold">Hip Hop Carti Tee</h2>
        <p className="text-sm text-gray-600">Oversized Graphic T-shirt, Summer Unisex</p>
        <p className="mt-2 font-bold">৳760</p>
        <Button className="mt-4 w-full">Buy Now</Button>
      </CardContent>
    </Card>

    {/* Repeat for more products */}
  </section>

  <footer className="bg-gray-900 text-gray-300 text-center py-6 mt-12">
    <p>Wovenheir is a proud part of ASF Group</p>
    <p>Office: Saterkul, Uttor Badda, Dhaka-1212</p>
    <p>Phone: 01769910116</p>
  </footer>
</main>

); }

