# docker-nginx-alpine
Based on the original docker nginx image, but with the nginx user in the www-data group

It currently uses `nginx:1.14-alpine` image as the base

| Tags |
|:-------:| 
| `:bare` |

## Example

```
docker run -d \
    -v /path/to/nginx.conf:/etc/nginx/nginx.conf \
    -v /path/to/vhost.conf:/etc/nginx/conf.d/vhost.conf \
    wonderous/nginx-alpine
```
