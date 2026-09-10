docker compose up
docker compose up -d (ig lihtsalt pane käima, ära anna mingi teksti)
docker compose down (kinni panemiseks)
docker compose exec {web} (mis nime panime? servicile ma web ja siis mingeid käskusi saad anda.)
docker compose exec web ls ..
docker compose exec web pwd
docker compose exec web bash --Saab mingi bashile ligi
docker compose stop
docker compose start  

docker compose up --build -d or ig docker compose build  ja siis...