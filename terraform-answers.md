# Ответы на задание по Terraform

## 1. Полный хеш и комментарий коммита, хеш которого начинается на aefea

**Команды:**  
`git log --oneline | grep aefea` 
`git show aefead2207`

**Полный хеш:** `aefead2207ef7e2aa5dc81a34aedf0cad4c32545`

**Комментарий:** `Update CHANGELOG.md`


## 2. Какому тегу соответствует коммит 85024d3?

**Команда:**  
`git describe --contains 85024d3`  

**Ответ:** тег **v0.12.23^0**


## 3. Сколько родителей у коммита b8d720? Напишите их хеши.

**Команда:**  
`git show b8d720 --pretty=format:"%P" --no-patch`  

**Ответ:** **2 родителя**

**Хеши родителей:**  
- `56cd7859e05c36c06b56d013b55a252d0bb7e158`  
- `9ea88f22fc6269854151c571162c5bcf958bee2b`

## 4. Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами v0.12.23 и v0.12.24

**Команда:**  
`git log v0.12.23..v0.12.24 --oneline`

**Ответ::**

- `33ff1c03bb` v0.12.24
- `b14b74c493` [Website] vmc provider links
- `3f235065b9` Update CHANGELOG.md
- `6ae64e247b` registry: Fix panic when server is unreachable
- `5c619ca1ba` website: Remove links to the getting started guide's old location
- `06275647e2` Update CHANGELOG.md
- `d5f9411f51` command: Fix bug when using terraform login on Windows
- `4b6d06cc5d` Update CHANGELOG.md
- `dd01a35078` Update CHANGELOG.md
- `225466bc3e` Cleanup after v0.12.23 release


## 5. Найдите коммит, в котором была создана функция func providerSource

**Команда:**  
`git log -S "func providerSource(" --oneline`

**Ответ:** Функция `providerSource` добавлена в коммите **8c928e8358** 

**Комментарий коммита:** "main: Consult local directories as potential mirrors of providers".



## 6. Найдите все коммиты, в которых была изменена функция globalPluginDirs

**Команда:**  
`git log -S "globalPluginDirs" --oneline`

**Ответ:** 
- `7c4aeac5f3` stacks: load credentials from config file on startup (#35952)
- `65c4ba7363` Remove terraform binary
- `125eb51dc4` Remove accidentally-committed binary
- `22c121df86` Bump compatibility version to 1.3.0 for terraform core release (#30988)
- `7c7e5d8f0a` Don't show data while input if sensitive
- `35a058fb3d` main: configure credentials from the CLI config file
- `c0b1761096` prevent log output during init
- `8364383c35` Push plugin discovery down into command package
 


## 7. Кто автор функции synchronizedWriters?

**Команда:**  
`git log -S "synchronizedWriters" --oneline`
`git show 5ac311e2a9 --pretty=full`

**Ответ:** 

**Автор:** **Martin Atkins** 

---

