Напиши стрілочну функцію getUserNames(users), яка прийматиме один параметр users — масив об’єктів користувачів. Функція має повертати масив імен усіх користувачів (властивість name) із масиву users.

Візьми код нижче і встав після оголошення своєї функції для перевірки коректності її роботи. У консоль будуть виведені результати її викликів.
1)
const getUserNames(users) => {
return users.map(users => users.name)
}
2)
const getUsersWithFriend(users, friendName) => {
 return users.filter(user => user.friends.includes(friendName));
}

const sortByDescendingFriendCount = (users) => {
  return users.toSorted((a, b) => b.friends.length - a.friends.length);
};
