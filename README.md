# Bootstrap-Model
    <div class="portfolio-modal modal fade" id="portfolioModal1" tabindex="-1" role="dialog" aria-hidden="true">
        <div class="modal-content">
            <div class="close-modal" data-dismiss="modal">
                <div class="lr">
                    <div class="rl">
                    </div>
                </div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-lg-8 col-lg-offset-2">
                        <div class="modal-body">
                            <!-- Project Details Go Here -->
                            <h2>EAST MAP</h2>
                            <p class="item-intro text-muted">The line of lights.</p>
                            <img class="img-responsive img-centered" src="img/portfolio/EAST.jpg" alt="">
                            <p> The line has opened its services for stations at Grimes Dyke, Seacroft Ring Road, Wyke Beck, Fforde Grene, St.James's Hospital, Quarry Hill, Eastgate and City Square.<br> In morning <span style="color:#8470FF;">(6:52 AM-7:32 PM)</span>, the tram is running after <strong> every 7-8 minutes </strong> including peak hours.<br> Additionaly, You can check route and exact timing by adding information in below text fields.</p>
							<div>
								<form id="info_form" action="tram.php" method="post" role= "form">
								<table align="center" cellspacing="10" style="border-collapse: separate;border-spacing: 0 5px;">
									<tr>
										<td style="">
											<strong>Your Nearest Station:&nbsp  </strong>
										</td>
										<td>
											<select type="text" id="nearest_station" name="nearest_station" autocomplete='off'>
											<option value="GrimesDyke">GrimesDyke</option>
											<option value="SeacroftRingRoad">SeacroftRingRoad</option>
											<option value="WykeBeck">WykeBeck</option>
											<option value="FfordeGrene">FfordeGrene</option>
											<option value="St.James'sHospital">St.James'sHospital</option>
											<option value="QuarryHill">QuarryHill</option>
											<option value="Eastgate">Eastgate</option>
											<option value="CitySquare">CitySquare</option>
											</select><br>
										</td>
									</tr>
									</br>
									<tr>
									<td>
											<strong> Destination Line  </strong>
									</td>
									<td height="70px">
										<label class="radio-inline">
										<input type="radio" name="optradio"  id="radio_north" value="north" autocomplete='off'>North
										</label>
										<label class="radio-inline">
										<input type="radio" name="optradio"  id="radio_south" value="south" autocomplete='off'>South
										</label>
										<label class="radio-inline">
										<input type="radio" name="optradio"  id="radio_east" value="east" autocomplete='off'>East
										</label>
									</td>
									</tr>
									</br>
									<tr>
										<td>
											<strong> Destination:  </strong>  
										</td>
										<td>
											<input type="text" name="destination" autocomplete='off'><br>
										</td> 
									</tr>
								</table>
								</form>
							</div>
							<br/>
							<br/>
                            <button type="button" id="east" onclick="find_route_time()" class="btn btn-primary"><i class="fa fa-times"></i> Check Route </button>
                        </div>
							<br/>
								<div>
                                <p id="response_info" style="border:3px; border-style:solid; border-color:#8470FF; padding: 1em;"></p>
								</div>
								
						    <ul class="list-inline">
                                <li>Date: May 2016</li>
                                <li>Contact: 0113 384 8484 </li>
                                <li>Email: information@leeds-supertram.co.uk</li>
                            </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
