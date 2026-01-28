INSERT INTO tbl_model (model_id, date_time_final, descricao_detalhada, html_form, html_model_doc, label, sigla) VALUES (NULL, NULL, 'Memorando é um tipo de documento que trata assuntos internos.', 'Assunto

                                                                              <label class="form-label">Interessado</label>
                                                                              <input type="text" class="form-control" id="Interessado">
                                                                              <div id="emailHelp" class="form-text">Informe o interessado.</div>

                                                                              <label for="documentBody" class="form-label">Descrição</label>
                                                                              <textarea class="form-control" id="documentBody" rows="3"></textarea>', '<!DOCTYPE html>
                                                                                          <html lang="en">
                                                                                          <head>
                                                                                              <meta charset="UTF-8">
                                                                                              <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                                                                              <title>Modelo Memorando</title>
                                                                                              <style>

                                                                                                  * {
                                                                                                      margin: 0;
                                                                                                      box-sizing: border-box;
                                                                                                  }

                                                                                                  .VisualizadorDocumento {
                                                                                                      width: 100%;
                                                                                                      padding: 10px;
                                                                                                      border: 1px solid #5c5c5c;
                                                                                                      margin: 0 auto;
                                                                                                  }

                                                                                                  .MargemDocumento {
                                                                                                      max-width: 900px;
                                                                                                      margin: 0 auto;
                                                                                                  }

                                                                                                  .LogoDocumento {
                                                                                                      text-align: center;
                                                                                                      margin-top: 50px;
                                                                                                      margin-bottom: 50px;
                                                                                                  }

                                                                                                  .LogoDocumento img {
                                                                                                      max-width: 100px;
                                                                                                  }

                                                                                                  .DataLocalCriacaoDocumento {
                                                                                                      text-align: right;
                                                                                                  }

                                                                                                  .InformacoesDocumento {
                                                                                                      text-align: center;
                                                                                                      margin-top: 100px;
                                                                                                      margin-bottom: 100px;
                                                                                                  }

                                                                                                  .InformacoesDocumento b,
                                                                                                  .InformacoesDocumento p {
                                                                                                      margin: 0;
                                                                                                      padding: 0;
                                                                                                  }

                                                                                                  .CorpoDocumento {
                                                                                                      text-align: left;
                                                                                                  }

                                                                                                  .CorpoDocumento p {
                                                                                                      margin: 0;
                                                                                                      padding: 0;
                                                                                                      white-space: pre-wrap;
                                                                                                      overflow-wrap: break-word;
                                                                                                  }

                                                                                                  .RodapeDocumento {
                                                                                                      text-align: center;
                                                                                                      margin-top: 80px;
                                                                                                      margin-bottom: 80px;
                                                                                                  }

                                                                                                  .RodapeDocumento p {
                                                                                                      margin: 0;
                                                                                                      padding: 0;
                                                                                                      white-space: pre-wrap;
                                                                                                      overflow-wrap: break-word;
                                                                                                  }

                                                                                              </style>
                                                                                          </head>
                                                                                          <body>
                                                                                              <div class="VisualizadorDocumento" id="VisualizadorDocumento">
                                                                                                  <div class="MargemDocumento" id="MargemDocumento">
                                                                                                      <div class="LogoDocumento" id="LogoDocumento">
                                                                                                          <img src="https://seeklogo.com/images/P/prefeitura-de-manacapuru-logo-2FBDF8B79C-seeklogo.com.png" alt="Logo do documento">
                                                                                                      </div><!--LogoDocumento-->

                                                                                                      <div class="DataLocalCriacaoDocumento" id="DataLocalCriacaoDocumento">
                                                                                                          <p>DataCriacaoDocumento</p>
                                                                                                      </div><!--DataLocalCriacaoDocumento-->

                                                                                                      <div class="InformacoesDocumento" id="InformacoesDocumento">
                                                                                                          <b>#Orgao</b>
                                                                                                          <p>#SecretariaCriacaoDocumento</p>
                                                                                                      </div><!--DataLocalCriacaoDocumento-->

                                                                                                      <div class="CorpoDocumento" id="CorpoDocumento">
                                                                                                          <p><b>Número de referência: </b>NumeroReferencia</p>
                                                                                                          <p><b>Interessado: </b>Interessado</p>
                                                                                                          <p><b>Descrição: </b>Descricao</p>
                                                                                                      </div><!--CorpoDocumento-->

                                                                                                      <div class="RodapeDocumento" id="RodapeDocumento">
                                                                                                          <b>#PessoaAssinante</b>
                                                                                                          <p>#SecretariaPessoaAssinante</p>
                                                                                                          <p>#DataAssinatura</p>
                                                                                                      </div><!--RodapeDocumento-->
                                                                                                  </div><!--MargemDocumento-->
                                                                                              </div><!--VisualizadorDocumento-->

                                                                                          </body>
                                                                                          </html>
', 'Memorando', 'MEM');

INSERT INTO tbl_mark (mark_id, code, desc_detalhada, nome, tipo_marca) VALUES (NULL, 0, 'Criacao', 'CRIACAO', 0);

INSERT INTO tbl_mark (mark_id, code, desc_detalhada, nome, tipo_marca) VALUES (NULL, 3, 'Tramitação de documento', 'TRAMITACAO_DOCUMENTO', 3);

INSERT INTO tbl_mark (mark_id, code, desc_detalhada, nome, tipo_marca) VALUES (NULL, 4, 'FINALIZACAO', 'FINALIZAR', 4);

INSERT INTO tbl_mark (mark_id, code, desc_detalhada, nome, tipo_marca) VALUES (NULL, 1, 'Assinar com senha', 'ASSINAR_COM_SENHA', 1);

INSERT INTO tbl_mark (mark_id, code, desc_detalhada, nome, tipo_marca) VALUES (NULL, 2, 'INCLUSAO_DE_COSSIGNATARIO', 'INCLUSAO_DE_COSIGNATARIO', 2);

CRIACAO(1, "Criação"),
ASSINAR_COM_SENHA(2, "Assinar com senha"),
INCLUSAO_COSSIGNATARIO(3, "Inclusão de conssignatário"),
TRAMITACAO_DOCUMENTO(4, "Tramitação de documento"),
FINALIZAR(5, "FINALIZACAO");
select * from tbl_mark;

select * from tbl_mobil;

select * from tbl_movement;

select * from tbl_document;

select * from tbl_model;
