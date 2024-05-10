#  Search Page

This repository is a open source project designed to display information about different salts and their availability in pharmacies. The page is built using React Js and fetches data from the provided API.

## Task Summary

- The search page consists of a search bar and button.
  ![img1](https://github.com/crypticCoder9/ReactApp/blob/main/home.png?raw=true)
- Upon entering a search term and submitting the form, the page displays the results for the corresponding salt.
- Each salt may have different forms, strengths, and packings available, with prices from different pharmacies shown.
- If a particular combination of form, strength, and packing is not available in any pharmacy, it is displayed as "No stores selling this product near you".
  ![img2](https://github.com/crypticCoder9/ReactApp/blob/main/data.png?raw=true)
- Selection buttons for form, strength, and packing are dynamic, with corresponding options displayed based on the user's selection.
- If a particular combination is not available in any store, the button will have a different design indicating its unavailability.
- A "more" button can be used to display additional options if there are more than two rows of selections.
  ![img3](https://github.com/crypticCoder9/ReactApp/blob/main/selection.png?raw=true)
- Users can hide the additional options, and their selection remains intact.
- ![img4](https://github.com/crypticCoder9/ReactApp/blob/main/more.png?raw=true)

## API

The provided API fetches data based on the search term entered by the user. It returns information about salt suggestions along with details about forms, strengths, packings, and availability in pharmacies.

### API Endpoint

https://backend.cappsule.co.in/api/v1/new_search?q=<search_term>&pharmacyIds=1,2,3

