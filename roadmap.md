r1:
- keep Sequelize logging on (enableSequelizeLog: true, where it should be off in the future (development.js): enableSequelizeLog: process.env.DB_LOG || false)
- reverted to DataTypes.JSON as MySQL 5.7 is provided in dev desktop.
- tested admin panel for updating users works fine.
- SEAN.js clone from git repo is most promising, seems better than (slightly out-dated) yeoman generated SEAN.JS
r0:
- intial config.
