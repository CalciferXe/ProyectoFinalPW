La carpeta back, como su nombre lo indica es el backend del proyecto, se recomienda tener una bd basada en postgreSQL para poder interactuar y que los comandos sequelize puedan utilizarse
en la carpeta .anv estan los datos que tiene que ingresar para conectar el codigo con la bd en postgre SQL ya iniciada
Antes de todo se recomienda instalar las dependencias de node y next:
npm install
Para iniciar se recomienda utilizar los siguientes lineas de codigo:
npm install pg pg-hstore sequelize
npm install sequelize-cli -g
npx sequelize init
npx sequelize db:create
npx sequelize db:migrate
npx sequelize db:seed:all  //Esta ultima utiliza los seeders que se tiene en la carpeta seeders, teniendo todo listo se recomienda utilizar dbeaver para hacer consultas a la base de datos
