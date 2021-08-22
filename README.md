# DISCORD_BOT_MINECRAFT
Plugin na bota do minecraft


```
config:
  database:
    HOST: 'localhost'
    PORT: 3306
    TABLE: 'test'
    USERNAME: 'root'
    PASSWORD: ''
  TOKEN_ID: 'ODQzODM2NTM1NTQ3NDk0NDAw.YKJqAw.-krXAiNfADDrZx_QJPnba7ePYF8'
  LISTENING: 'Jestem botem ktory rozdaje nagrody'
  ID_CHANNEL: '843850570855088168'
  TITLE_NAME: 'MINECRAFT | NAGRODA'

  INVENTORY_NAME: '&aNagroda'

  VERYFICATION_DISCORD: '&4Błąd: &cNie zweryfikowałeś się na discord!'
  MESSAGE_REWARD: '&aGratualcje odebrales nagrode za dolaczenie na discord!'
  MESSAGE_ARLEADY_REWARD: '&4Błąd: &cOdebrałeś już swoją nagrode!'```

reward:
  '1':
    invName: '&7Odbierz nagrode'
    invLore:
      - ''
      - '&7Status discord: {STATUS_REWARD_DISCORD}'
      - '&7Status minecraft: {STATUS_REWARD_MINECRAFT}'
      - ''
      - '&7Nagroda: &72x chest'
      - ''
      - '&fLewy &cAby odebrac nagrode!'
    invSlot: 2
    rewardItem: 'CHEST' #ppodajemy nazwy z minecraft przedmiotow`
    rewardAmountItem: 2
    rewardItemName: '&7Skrzynka' # nazwa itemu jaki gracz otrzyma jesli damy `null` nazwy nie bedzie
    rewardItemLore: #opis itemu jaki gracz otrzyma jesli damy `null` opisu nie bedzie
      - '&7OPIS'
      - '&fOPIS 1'
      - '&6OPIS 2'
    rewardItemsEnchants:
      - 'null' ## przyklad: 'DURABILITY:3'  dodaje enchant unbreaking 3 dlatego itemku
    commands: 'pex user {player} group set VIP' ## jesli wpiszemy 'null' gracz nie otrzyma rangi
