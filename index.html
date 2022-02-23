import requests
import telebot
import random
from hashlib import md5
from telebot import types
from time import sleep
token = "5125472697:AAH75t0Q7eUcvjLZeidrDY-HHSUl6wuTWYo"
bot = telebot.TeleBot(token)
@bot.message_handler(commands=['start'])
def send_welcome(message):
  first = message.chat.first_name
  bot.reply_to(message,f"مرحباً {first}في بوت التجميع ارسل /Dark لتشغيل البوت  .")
@bot.message_handler(commands=['create'])
def start(message):
    if message.chat.type == 'private':
        sent = bot.send_message(message.chat.id, text='مرحبا بك عزيزي \n\n ارسلكود الدعوه الخاص بك بهذا النمط :\n : رقم هاتفك')
        bot.register_next_step_handler(sent, login)
def Get(message):
  	code = message.text.split(':')[0]
    dark = message.text.split(':')[1]
    for i in range(int(dark)):
    	cc = '0123456789'
    	xx = '010','011','012','015'
    	phone = random.choice(xx)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)
    	pp = random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)+random.choice(cc)
    	ppp=md5(pp.encode()).hexdigest()
    	url = "https://kimball99.com/api/user/reg"
    	r = requests.get('https://kimball99.com/').cookies
    	a = r['XSRF-TOKEN']
    	n = r['laravel_session']
    	header= {"accept-encoding":"gzip, deflate, br","accept-language":"ar-AE,ar;q=0.9,en-US;q=0.8,en;q=0.7","accept":"*/*","cache-cntrol":"no-cache","user-agent":"Mozilla/5.0 (Linux; Android 9; SM-J610F) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/98.0.4758.60 Mobile Safari/537.36","referer":"https://kimball99.com/","cookie":f"XSRF-TOKEN={a}; laravel_session={n}"}
    	data = {"phone":phone,"captcha":"123456","invite_code":code,"password":ppp,"deal_password":ppp,"type":"yhzc"}
    	k = requests.post(url,headers=header,data=data)
    	if '{"data":[],"code":0,"message":""}' in k.text:
    		bot.send_message(message.chat.id,f'<strong>{phone}\n{pp}</strong>',parse_mode='html')
    	else:
    		print('Error')
bot.polling(True)
