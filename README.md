# Warehouse Reallocation Strategy – Multi-City Logistics

This project dives into real-world supply chain data to figure out where delivery delays are happening — and how we can fix them just by rethinking warehouse placements.

Turns out, some warehouses are slowing things down big time. So I explored whether shifting shipments from those underperforming sites to better ones could reduce delays across the board.

---

## What’s this about?

Imagine running shipments to 15+ countries, but deliveries keep getting delayed. Customers aren’t happy, and shipping costs pile up.

This notebook breaks down:
- Which countries face the worst delays?
- Which warehouses are responsible?
- Are some countries just too far from their current warehouse?
- And finally — can we actually simulate a reallocation and prove it’d work?

Spoiler: yep.

---

## What I did

- Cleaned and explored 10,000+ shipment records  
- Engineered custom features like `Delivery_Delay_Days`, `Freight_per_KG`, and `Delay_per_Unit`  
- Used boxplots, heatmaps, and visual breakdowns to spot red flags  
- Simulated moving shipments from a bad warehouse to a better one  
- Backed it up with metrics and a final recommendation

---

## Tools & Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## Key Takeaways

- Some warehouses consistently cause massive delays  
- A few countries are just too far from their assigned warehouse  
- Reassigning even part of the load can reduce average delays and cut risk  
- You don’t need a full system overhaul — smart tweaks can go a long way  

---

## Files in this repo

- `Warehouse_Reallocation_Strategy.ipynb` – Main notebook with full analysis + visuals  
- `Dataset` – The raw shipment data  

---

Thanks for checking it out! 🚀
