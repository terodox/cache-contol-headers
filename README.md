# static-html-page
Simple static html page for testing Amplify static site deployments

## Routes and headers

| Route | Cache Control header |
|---|---|
| /public/iris-nebula-max-age.jpeg | max-age=30, stale-while-revalidate |
| /public/iris-nebula-s-maxage.jpeg | s-maxage=30, stale-while-revalidate |
| /public/iris-nebula-max-age-larger-than-s-maxage.jpeg | s-maxage=30, max-age=60, stale-while-revalidate |
| /public/iris-nebula-max-age-less-than-s-maxage.jpeg | s-maxage=60, max-age=30, stale-while-revalidate |
 
