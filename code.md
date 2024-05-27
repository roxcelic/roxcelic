# Below I'll display my most prideful code snippets:

### JavaScript:
```javascript
export async function fetchDataFromWorker() {
    try {
      const response = await fetch("https://api.roxcelic.love/");
      if (response.ok) {
        const data = await response.json();
        return data
      } else {
        console.error("Error fetching data from Cloudflare Worker:", response.status);
      }
    } catch (error) {
      console.error("An error occurred while fetching data:", error);
    }
  }
```
(It isn't this exactly, but it's the closest I can get to showing my API code)

### c#
```cs
if (transform.GetChild(0).GetChild(0).childCount > 0 && Input.GetButtonDown("Menu_Back") && Menu_Back == true)transform.GetChild(0).GetChild(0).transform.GetComponent<host>().ChangeMenu(menus[transform.GetChild(0).GetChild(0).GetChild(0).GetComponent<Menu_Data>().back]);
```
(Just a really long and funky line for my Unity game. I get it could be shorter, but it's funny)

Thanks for listening. Wanna go [back](https://github.com/roxcelic)?