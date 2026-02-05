SHOW DATABASES;
-- DROP DATABASE copa_do_mundo; -- apaga o bando de dado

USE copa_do_mundo; -- selecionar banco de dado
SHOW TABLES; -- mostra as tabelas do banco selecionado
DESC jogadores; -- mostra as config da tabela

SELECT * FROM GRUPOS;

INSERT INTO grupos(nome)
VALUES ("A"),
	   ("B"),
       ("C"),
       ("D"),
       ("E"),
       ("F"),
       ("G");
SELECT * FROM selecoes;

INSERT INTO selecoes(nome, qtd_copa_vencida, id_grupo)
VALUES ("Brasil", 5, 1),
	   ("Argentina", 3, 1),
       ("Alemanha", 4, 1),
       ("França", 2, 1),
       
       ("Espanha", 1, 2),
       ("Japão", 0, 2),
       ("Marrocos", 3, 2),
       ("Sérvia", 0, 2),
       
       ("Itália", 4, 3),
       ("Croacia", 0, 3),
       ("Egito", 0, 3),
       ("Nigéria", 0, 3),
       
       ("Equador", 0, 4),
       ("Colombia", 0, 4),
       ("Paraguai", 0, 4),
       ("Inglaterra", 1, 4),
       
       ("Senegal", 0, 5),
       ("Estados Unidos", 0, 5),
       ("Portugal", 0, 5),
       ("Bélgica", 0, 5),
       
       ("Holanda", 0, 6),
       ("Suiça", 0, 6),
       ("Suécia", 0, 6),
       ("Irã", 0, 6),
       
       ("Coreia do Sul", 0, 7),
       ("Aústria", 0, 7),
       ("Australia", 0, 7),
       ("Arabia Saudita", 0, 7);
       
DESC jogadores;
       
SELECT * FROM jogadores;
       
INSERT INTO jogadores(nome, n_camisa, id_selecao)
VALUES ("Neymar", 10, 1),
       ("Messi", 10, 2),
       ("Jamal", 10, 3),
       ("Mbappe", 10, 4),
       
       ("Yamal", 10, 5),
       ("Ritsu", 10, 6),
       ("Brahim", 10, 7),
       ("Tadić", 10, 8),
       
       ("Lorenzo", 10, 9),
       ("Modrić", 10, 10),
       ("Mohamed", 10, 11),
       ("Joe Aribo", 7, 12),
       
       ("Kendry", 10, 13),
       ("James R", 10, 14),
       ("Miguel", 10, 15),
       ("Palmer", 10, 16),
       
       ("Mané", 10, 17),
       ("Diego Luna", 10, 18),
       ("Bernardo Silva", 10, 19),
       ("Leandro Trossard", 10, 20),
       
       ("Depay", 10, 21),
       ("Xhaka", 10, 22),
       ("Forsberg", 10, 23),
       ("Jahanbakhsh", 10, 24),
       
       ("Lee Kang", 10, 25),
       ("Andreas ", 10, 26),
       ("Ajdin Hrustic", 10, 27),
       ("Salem", 10, 28);
       
INSERT INTO estadios(nome, cidade, pais, capacidade)

VALUES ("Narendra Modi Stadium", "Ahmedabad", "Índia", 132.000),
	   ("Rungrado 1st of May Stadium", "Pyongyang", "Coreia do Norte", 114.000),
       ("Michigan Stadium", "Ann Arbor", "EUA", 107.601),
       ("Beaver Stadium", "State College", "EUA", 106.304),
       ("Melbourne Cricket Ground", "Melbourne", "Austrália", 100.024);
       
SELECT * FROM SELECOES;

DESC partidas;
INSERT INTO partidas(id_partida,id_selecao_a, id_selecao_b, id_estadio, gols_selecao_a, gols_selecao_b, horario, bilheteria)
VALUES
(1,1,2,1,2,1,'2026-10-20 19:00:00',1250000.00),
(2,3,4,2,3,2,'2026-10-21 16:30:00',980000.00),
(3,5,6,3,1,0,'2026-10-22 20:45:00',850000.00),
(4,7,8,4,2,1,'2026-10-24 15:00:00',720000.00),
(5,9,10,5,2,1,'2026-10-25 18:30:00',950000.00),
(6,11,12,1,1,0,'2026-10-26 14:00:00',680000.00),
(7,13,14,2,0,2,'2026-10-27 21:15:00',820000.00),
(8,15,16,3,1,2,'2026-10-28 17:45:00',1120000.00),
(9,17,18,4,2,0,'2026-10-29 19:30:00',780000.00),
(10,19,20,5,1,2,'2026-10-30 16:00:00',1030000.00),
(11,21,22,1,3,1,'2026-11-01 15:30:00',840000.00),
(12,23,24,2,1,0,'2026-11-02 20:00:00',650000.00),
(13,25,26,3,2,1,'2026-11-03 18:00:00',760000.00),
(14,27,28,4,1,0,'2026-11-04 14:30:00',590000.00);

SELECT * FROM partidas;

