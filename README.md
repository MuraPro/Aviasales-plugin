# Aviasales Plugin  
A React + Redux Toolkit plugin with lazy-loading and ticket filtering for flight search functionality.

## Technologies Used  
- **Frontend:** React, Redux Toolkit, React Lazy / Suspense  
- **Build System:** Vite  
- **State Management:** Redux Toolkit (slice architecture)  
- **Lazy Loading:** Code‐splitting via React.lazy + dynamic imports  
- **Filtering Logic:** Ticket filtering module (price, carrier, stops)  
- **Styling/Components:** [if used: e.g., CSS Modules / Styled Components / Bootstrap]  

## Features  
- Lazy-loaded modules for performance optimization  
- Ticket search and filter system (price, carrier, direct vs stops)  
- Redux Toolkit state slice for tickets + filters  
- Responsive layout (mobile/desktop)  
- Example login/test credentials [if applicable]  

## Architecture & State Management  
### Hooks Version  
- Built using React Hooks + Context API  
- Local component state for filters and tickets  

### Redux Toolkit Version  
- Separate branch (`redux-version`) migrating state to Redux Toolkit  
- Tickets slice (actions: fetchTickets, filterTickets)  
- Filters slice (actions: setFilter, clearFilter)  
- Usage of RTK query or async thunks for data fetching  

## Demo  
Live demo: [https://aviasels-plugin.vercel.app/](https://aviasels-plugin.vercel.app/)  






